---
layout: splash
title: " "
permalink: /
hidden: true
#header:
#  overlay_color: "#ffffff"
#  overlay_image: /assets/images/sgsa-officers/officers2023.JPG
---

## About us

The Statistics Graduate Student Association, (SGSA), is an organization that provides the best possible environment to encourage the interaction between students and faculty by bestowing forums for students to connect with faculty as they discuss their current research, encouraging participation in academic events outside of the traditional classroom setting, and by giving back to the community that supports all of us in the A&M family.

## Upcoming Events


<html>
  <head>
    <title>Google Calendar API Quickstart</title>
    <meta charset="utf-8" />
  </head>
  <body>
    <p>Google Calendar API</p>
    <pre id="content" style="white-space: pre-wrap;"></pre>

    <script type="text/javascript">
      // API key from the Developer Console
      var API_KEY = '219362777407-s1ai98e59rkhu9k4ijmjr46pnbodunet.apps.googleusercontent.com';

      // Array of API discovery doc URLs for APIs used by the quickstart
      var DISCOVERY_DOCS =
        ["https://www.googleapis.com/discovery/v1/apis/calendar/v3/rest"];

      var CALENDAR_ID = 'en.usa#holiday@group.v.calendar.google.com';


      function start() {
        gapi.client.init({
          'apiKey': API_KEY,
          'discoveryDocs': DISCOVERY_DOCS,
        }).then(function() {
          listUpcomingEvents();
        });
      }

      function onLoad() {
        gapi.load('client', start);
      }

      /**
       * Displays a list of events from the public calendar.
       * You'll need to tweak the rest to show the data you like.
       */

      function appendPre(message) {
        var pre = document.getElementById('content');
        var textContent = document.createTextNode(message + '\n');
        pre.appendChild(textContent);
      }

      function listUpcomingEvents() {
        gapi.client.calendar.events.list({
          'calendarId': CALENDAR_ID,
          'timeMin': (new Date()).toISOString(),
          'showDeleted': false,
          'singleEvents': true,
          'orderBy': 'startTime'
        }).then(function(response) {
          var events = response.result.items;
          appendPre('Upcoming holidays:');
          if (events.length > 0) {
            for (i = 0; i < events.length; i++) {
              var event = events[i];
              var when = event.start.dateTime;
              if (!when) {
                when = event.start.date;
              }
              appendPre(event.summary + ' (' + when + ')');
            }
          } else {
            appendPre('No upcoming events found.');
          }
        });
      }

    </script>
    <script async defer src="https://apis.google.com/js/api.js" onload=onLoad();>
    </script>

  </body>
</html>

