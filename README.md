# Text-to-Speech Application
  
This is a project built with [Chef](https://chef.convex.dev) using [Convex](https://convex.dev) as its backend.
 You can find docs about Chef with useful information like how to deploy to production [here](https://docs.convex.dev/chef).
  
This project is connected to the Convex deployment named [`artful-tapir-838`](https://dashboard.convex.dev/d/artful-tapir-838).
  
## Project structure
  
The frontend code is in the `app` directory and is built with [Vite](https://vitejs.dev/).
  
The backend code is in the `convex` directory.
  
`npm run dev` will start the frontend and backend servers.
<pre>
  🎙️ Key Features:
Voice Options:

Multiple voice selection (male, female, various accents)
Automatic categorization by gender and accent (American, British, Australian, Indian)
Default voice fallback

  >>Audio Controls:

Adjustable speech speed (0.5x to 2x)
Volume control (0% to 100%)
Play, pause, resume, and stop functionality
Real-time progress tracking with visual progress bar

  >>User Interface:

Clean, minimal design with intuitive controls
Large text input area with character counter
Responsive layout that works on all devices
Visual feedback during speech playback
Status indicators (Speaking, Paused, Ready)

  ??Accessibility Features:

High contrast support
Reduced motion support for users with vestibular disorders
Proper ARIA labels and semantic HTML
Keyboard navigation support
Screen reader friendly

  >>User Experience:

Save user preferences (voice, speed, volume, last text)
Text history with quick reload functionality
Toast notifications for user feedback
Gradient background for visual appeal

  >>Technical Implementation:

Uses Web Speech API for text-to-speech
Convex backend for user preferences and history
Real-time data synchronization
Responsive design with Tailwind CSS

The app automatically saves your preferences and text history when you're signed in. You can select different voices, adjust speed and volume, and easily replay previous texts from your history. 
The interface is designed to be accessible and user-friendly for all users.

Try typing some text and experimenting with different voices and settings!
</pre>

