---
title: Visual Studio Code
tab: vscode
---

### Overview

GitLive's video-calling feature allows you to call teammates straight from your IDE and work together on files like you would on a Google Docs collaboration. This feature will undoubtedly boost your productivity when you want to fix code issues with a teammate.


### Instructions
#### Step 1

 Next to a teammate's name, you will find a phone icon allowing you to place a call.

![Call Teammate](/uploads/vscode-call-teammate.jpeg "Call Teammate"){:class="screenshot"}

You can also call any teammate through the command palette. First, select “Call a Teammate” and you will have a dropdown list of all of your collaborators on the project.

![Call Teammate Command Pallete](/uploads/vscode-call-teammate-command-pallete.jpg "Call Teammate Command Pallete"){:class="screenshot"}

#### Step 2

 You will then get a pop-up notification that you have sent the request to call and are waiting for your teammate to accept it. The call gets cancelled automatically after 15 seconds, leaving your teammate with a notification about the missed call and the option to call back.

![Caller Popup](/uploads/video-calling-caller-popup.jpg "Video Calling Popup"){:class="screenshot"}

#### Step 3

The teammate you are looking to call will then get a pop-up notification. Once they answer, the call opens up in their browser.

![Receiver Popup](/uploads/vscode-video-calling-receiver-popup.jpg "Receiver Popup"){:class="screenshot"}

#### Call Interface
The call is launched through a web app, that opens up after a call has been answered.

![Video Call](/uploads/calling-main-img.jpg "Video Call"){:class="screenshot"}

#### Calling Features

There are four main controls available whilst on the call. You can choose to mute yourself, to enable or disable video, to screen share or codeshare.

<table class="table-custom">
  <tbody>
    <tr>
    <td class="td-custom">
              <img src="/uploads/mute-mic-option.jpg" alt="Mute Mic Option">
            </td>
    <td class="td-custom">
              <img src="/uploads/enable-video-option.jpg" alt="Enable Video Option">
            </td>
        <tr>
            <td class="td-custom">
              <img src="/uploads/share-screen-option.jpeg" alt="Share Code Option">
            </td>
            <td class="td-custom">
              <img src="/uploads/share-code-option.jpg" alt="Share Screen Option">
            </td>
        </tr>
    </tr>
  </tbody>
</table>


#### CodeShare

Selecting the share code option opens up a modal, which shows the different projects you have open and the different methods of pair programming that are available. 

![Share Code](/uploads/codeshare-gitlive-options.jpg "Share Code"){:class="screenshot"}

Selecting the GitLive option is the quickest way to start a collaboration session in your IDE. This means that any file you open will also open in the IDE of the other participant on the call, allowing you to edit together as you would in a google doc. You can even codeshare on files that aren't under source control (such as files ignored in Git) or files from outside the directory (such as external libraries’ source files). 

![Share Code](/uploads/vscode-video-call-share-code.png "Share Code"){:class="screenshot"}

By default, you will automatically follow each other's cursors when scrolling or switching files. You can disable following from within the IDE to work independently.

![Follow Cursor](/uploads/vscode-call-follow-cursor.jpeg "Follow Cursor"){:class="screenshot"}

If you have Live Share installed, you can choose to use that to collaborate, instead of GitLive's proprietary code sharing solution. You can find more information about using Live Share [here](/docs/supportforlivesharecodewithme/){:class="internal-link"}. 


#### ScreenShare

You have the option to share your screen with the other participant on the call, which can be useful if you need to share content from your browser or terminal. You can share a specific window or your entire desktop.

![Receiver Screen](/uploads/video-calling-receiver-screen.png "Receiver Screen"){:class="screenshot"}

#### Enable Video

When you first join a call, it will default to an audio call. At any point, any participant can choose to turn on their video to begin a video call.

![Enable Vieo](/uploads/video-calling-videos.jpeg "Enable Video"){:class="screenshot"}

#### Mute Microphone

If you choose to mute your microphone, other users will see the mute icon next to your name, so that they are aware of the fact that your microphone has been muted.

![Mute Microphone](/uploads/video-calling-muted-2.jpg "Mute Microphone"){:class="screenshot"}

#### Busy Status While on a Call
In addition to the green (online) or orange (away) dot beside a user’s avatar in the GitLive tab, there is also a busy (red) status. During a call, the status indicator for both participants will turn red and others won’t be able to call either teammate until their call is complete.

![Busy Status](/uploads/vscode-busy-indicator.jpeg "Busy Status "){:class="screenshot"}


#### Ending the Call

Once the call has been ended, a message will appear notifying both participants. At this point, you can close the tab in your browser and return to your IDE.

![End the Call](/uploads/video-call-ended.jpg "End the Call"){:class="screenshot"}


[Suggest an Edit to this Page](https://github.com/GitLiveApp/GitLive/edit/master/_sections/videocalling-vscode.md){:class="uk-button uk-button-success"}

