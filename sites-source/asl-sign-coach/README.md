# ASL Sign Coach

Mobile-first ASL learning prototype with a visual practice loop: **See it. Sign it. Check it. Remember it.**

The learning path contains 24 short lessons in three levels. The next level unlocks after six lesson reflections in the previous level. Lesson completion is based on learner self-checks, not computer-vision grading.

## Recognition and privacy

- MediaPipe hand, face, and pose landmarks run in the browser. Camera frames are processed locally and are not uploaded or recorded by this app.
- Progress and self-check results stay in this browser using local storage.
- The current computer vision checks camera framing, hand and face landmark visibility, hand movement, and facial movement cues. It does not recognize or grade ASL vocabulary or grammar. Use a Deaf ASL instructor and the linked ASL University lessons for linguistic accuracy.
- Camera permission and an internet connection are needed to load the vision models. Browsing lessons and saved progress work without the camera.

## Local development

Open `index.html` from a static web server. Camera access requires HTTPS or localhost. There is no build step, account, paid API, or backend.
