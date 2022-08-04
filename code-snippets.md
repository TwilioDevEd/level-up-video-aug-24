# Code snippets

## CURL request for token

curl -X POST http://localhost:5000/token -H "Content-Type: application/json" -d '{"identity": "Sarah"}'

## Video Room Monitor

<script src="https://cdn.jsdelivr.net/npm/@twilio/video-room-monitor/dist/browser/twilio-video-room-monitor.js"></script>

      Twilio.VideoRoomMonitor.registerVideoRoom(room);
      Twilio.VideoRoomMonitor.openMonitor();