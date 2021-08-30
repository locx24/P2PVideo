# PeerToPeerVideo
Creates a WebRTC PeerConnection and shares video between two peers without a signalling server 

Please modify index.html to accomplish the following:
1. Add an audio track to the video stream
2. Create a video stream of the local screen using getDisplayMedia
3. Add a video element, alongside the local video, that displays the screen
4. Add the shared screen video track to the peer media stream
5. When a remote connection is made, display the remote shared screen alongside the remote video

The final index.html should have 2 video elements diaplying the local camera and local screen, and two video elements displaying the remote video and remote screen.
The peers should be able to see each other's cameras, screens and to speak with each other.
