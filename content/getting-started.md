---
title: "Getting Started"
description: "A step-by-step guide for caretakers setting up E2S Assistant for someone else."
date: 2026-10-19
layout: "landing"
---

<style>
  h2[id], h3[id] { scroll-margin-top: 6.5rem; }
  @media (prefers-reduced-motion: no-preference) {
    html { scroll-behavior: smooth; }
  }
</style>

{{< hero title="Setting up E2S for" titleAccent="someone you care about." subtitle="Thank you for helping! This guide walks you through setting up E2S Assistant from start to finish: permissions, voice, vibrations, navigation, food, calls, the Action Button and more. Plan on about **30–45 minutes**, and do it **together** with the person who'll use E2S if you can." >}}

{{< pills >}}
  {{< pill icon="mdi:clock-outline" >}}About 30–45 minutes{{< /pill >}}
  {{< pill icon="mdi:account-multiple-outline" >}}Best done together{{< /pill >}}
  {{< pill icon="mdi:toggle-switch-outline" >}}Everything is optional{{< /pill >}}
  {{< pill icon="mdi:undo-variant" >}}Change anything later{{< /pill >}}
{{< /pills >}}

{{< buttons >}}
  {{< button href="#step-1" variant="primary" size="lg" icon="mdi:rocket-launch-outline" >}}Start the guide{{< /button >}}
  {{< button href="/features/" variant="ghost" size="lg" icon="mdi:star-four-points-outline" >}}See all features{{< /button >}}
{{< /buttons >}}

{{< /hero >}}

{{< section width="narrow" >}}

> [!TIP]
> **One golden rule for caretakers:** E2S belongs to the person using it. Set it up *with* them, not *for* them. Explain each choice out loud, let them make the final call, and show them how to change things later. Independence is the whole point!

## Before you begin {#before-you-begin}

| You'll need | Why |
|---|---|
| An iPhone with the latest iOS | E2S uses the newest accessibility and on-device AI features |
| An iPhone **Pro** model (optional) | Pro models have the **LiDAR** sensor used for room scans, indoor guidance and depth-based Path Alerts |
| An iPhone with Apple Intelligence (optional) | Lets E2S take a "closer look" at hard-to-read text |
| A quiet room and a charged battery | Voice setup works best without background noise |
| The user's VoiceOver settings, if they use VoiceOver | So E2S fits how they already use their phone |

{{< /section >}}

{{< section >}}

## Jump to a step {#jump}

{{< feature-grid >}}
  {{< feature-card title="Install & safety" icon="mdi:download-circle-outline" url="#step-1" >}}
  Get E2S and go over the safety notice together.
  {{< /feature-card >}}
  {{< feature-card title="Permissions" icon="mdi:shield-key-outline" url="#step-3" >}}
  The permission tutorial: what each one does.
  {{< /feature-card >}}
  {{< feature-card title="Voice & vibrations" icon="mdi:account-voice" url="#step-4" >}}
  How E2S talks, listens, and vibrates.
  {{< /feature-card >}}
  {{< feature-card title="Getting around" icon="mdi:map-marker-path" url="#step-6" >}}
  Directions, Path Alerts, and indoor maps.
  {{< /feature-card >}}
  {{< feature-card title="Calls & shortcuts" icon="mdi:phone-outline" url="#step-9" >}}
  Hands-free calls, messages, Siri, and the Action Button.
  {{< /feature-card >}}
  {{< feature-card title="Privacy & lock" icon="mdi:lock-outline" url="#step-11" >}}
  Lock Settings with Face ID, and privacy choices.
  {{< /feature-card >}}
{{< /feature-grid >}}

{{< /section >}}

{{< section width="narrow" >}}

## Step 1: Install E2S {#step-1}

{{< steps >}}
{{< step number="1" title="Download it" >}}
Get E2S free from the [App Store]([APP STORE LINK]). There are no accounts to create, no sign-ups and no payments.
{{< /step >}}
{{< step number="2" title="Open it with the user" >}}
Hand the phone to the person who'll use E2S, or sit next to them. The first screens matter, so they should hear them.
{{< /step >}}
{{< /steps >}}

## Step 2: Go over the safety notice together {#step-2}

When E2S opens for the first time, it shows a safety notice. **The user should accept it themselves**, after hearing it read in full.

> [!WARNING]
> Make sure these points really land:
> - E2S **helps**, but it doesn't replace a white cane, guide dog, orientation and mobility training, or a sighted guide.
> - Directions, Path Alerts, text reading and allergen checks **can be wrong**.
> - E2S can't call for help on its own. **In an emergency, call 911.**
>
> The full rules are in the [Terms of Use](/terms-of-use/).

## Step 3: Run the permission tutorial {#step-3}

Go to **Settings → App access → Start permission tutorial**. E2S explains each permission one at a time, out loud. **Every single one is optional.** If you skip one, the features that need it simply stay off.

| Permission | What E2S uses it for | Skip it and… |
|---|---|---|
| **Camera** | Reading text, scene descriptions, finding objects and signs, Path Alerts, barcodes | Seeing and reading features are off |
| **Microphone** | Hearing voice commands and sound alerts (sirens, horns) | Use touch only |
| **Speech recognition** | Turning speech into commands, on the iPhone | Voice commands are off |
| **Location** | Walking and transit directions, nearby places, weather | Navigation is off. Choose **Precise Location**, or directions won't be accurate |
| **Contacts** | "Call Mom", "Text Sam" | Calls and messages by name won't work |
| **Calendars** | Reading out upcoming events | No calendar answers |
| **Reminders** | Grocery lists and to-dos | Lists stay inside E2S only |
| **Apple Music** | Playing music by voice | No music by voice |
| **Live Activities** | Timers and directions on the Lock Screen | They show only inside the app |

You can review or change these anytime in **Settings → App access**, or with the **Change access in iPhone Settings** button.

## Step 4: Set up how E2S talks and listens {#step-4}

Go to **Settings → Touch, Voice, & Haptics**.

{{< tabs >}}

{{< tab name="E2S voice" icon="mdi:account-voice" >}}
Open **E2S voice** and choose a voice and speed. Let the user pick; they'll be listening to it every day! Faster isn't always better outdoors, where traffic noise competes.
{{< /tab >}}

{{< tab name="Voice control" icon="mdi:microphone-outline" >}}
Open **Voice control**:
- **Keep listening until I say stop:** E2S keeps listening after each answer. Even when this is off, E2S still listens during directions, recipes, indoor guidance and when it's waiting for an answer.
- **Run voice setup:** lets the user change settings just by talking. Try: *"read my settings," "talk faster," "turn off vibrations," "warn me 200 feet before turns."*
{{< /tab >}}

{{< tab name="Listening" icon="mdi:ear-hearing" >}}
Open **Listening & voice focus** for noisy places. Turn on **noisy-place mode** and **ignore distant voices** if the user takes the bus, shops in busy stores or lives with a loud household.
{{< /tab >}}

{{< tab name="VoiceOver users" icon="mdi:human-cane" >}}
E2S works alongside VoiceOver. Have the user try a few commands with VoiceOver on, so you both know how the two voices sound together. If they clash, slow E2S's voice down a little, or keep VoiceOver's speech rate where the user is used to it.
{{< /tab >}}

{{< /tabs >}}

## Step 5: Choose vibrations {#step-5}

Go to **Settings → Touch, Voice, & Haptics → Haptic cues**. E2S uses vibrations for things like "I'm listening now," turns and warnings.

{{< steps >}}
{{< step number="1" title="Feel each one" >}}
Play each pattern and let the user hold the phone. Can they tell them apart?
{{< /step >}}
{{< step number="2" title="Make warnings stand out" >}}
Obstacle and safety warnings should feel the **strongest and most different** from everything else.
{{< /step >}}
{{< step number="3" title="Practice the listening vibration" >}}
E2S vibrates when it's ready to listen. Teach the user to **wait for that vibration** before speaking.
{{< /step >}}
{{< /steps >}}

## Step 6: Set up navigation {#step-6}

Go to **Settings → Navigation and Guidance**.

- **Direction settings:** walking or transit by default, avoiding highways, and how early E2S announces turns.
- **Path alerts:** warnings about obstacles ahead, using the camera (and LiDAR on Pro models).
- **LiDAR maps:** the saved indoor-map library (see Step 7).

> [!IMPORTANT]
> **Do the first few trips together.** Walk a familiar route with E2S giving directions while you stay beside the user. You'll both learn how early it announces turns and how it handles crossings, and you can adjust settings on the spot.

## Step 7: Scan important rooms (Pro iPhones) {#step-7}

If the iPhone has LiDAR, you can scan rooms like the kitchen, living room or office, so E2S can help the user find their way around inside.

{{< steps >}}
{{< step number="1" title="Scan slowly" >}}
Walk the room slowly, pointing the phone at walls, furniture and doorways. Good light helps. If the app closes partway through, E2S saves your progress so you can pick up where you left off.
{{< /step >}}
{{< step number="2" title="Give it a simple name" >}}
Save the scan in **Settings → LiDAR maps** with a short, unique name the user will remember, like **Kitchen** or **Bedroom**. Two scans with the same name will confuse things.
{{< /step >}}
{{< step number="3" title="Practice loading it" >}}
Have the user say: *"Load indoor scan Kitchen."* A floating map appears if **Floating indoor map** is turned on.
{{< /step >}}
{{< /steps >}}

> [!NOTE]
> Loading a map loads the **layout**. E2S doesn't know where the user is standing until indoor guidance starts. Rescan if furniture moves.

## Step 8: Food, allergies and online services {#step-8}

{{< tabs >}}

{{< tab name="Allergies & diet" icon="mdi:food-apple-outline" >}}
Go to **Settings → Food and Nutrition → Food and nutrition settings** and add every allergy and diet need. The user can also just say: *"I'm allergic to peanuts."*

**Barcode checks are a helper, not a guarantee.** For serious allergies, always confirm the label another way.
{{< /tab >}}

{{< tab name="Web search" icon="mdi:magnify" >}}
Web answers need the user's own **Brave Search** key. Add it in **Settings → Online Services → Online service settings**. It's stored in the iPhone's secure Keychain.
{{< /tab >}}

{{< tab name="Talking Books" icon="mdi:book-open-variant" >}}
Set up audiobooks in **Settings → Online Services → Talking Books**.
{{< /tab >}}

{{< /tabs >}}

## Step 9: Hands-free calls and messages {#step-9}

By default, E2S reads a call or message back and asks *"Should I…? Say yes or no,"* then opens the Phone, FaceTime or Mail screen to finish. To make it fully hands-free, turn on **Settings → Touch, Voice, & Haptics → Voice control → Send messages and place calls without a button**, then create these **5 shortcuts** in Apple's Shortcuts app. The names must match **exactly**:

| Shortcut name | What it does |
|---|---|
| `E2S Call` | Phone call |
| `E2S FaceTime` | FaceTime video |
| `E2S FaceTime Audio` | FaceTime audio |
| `E2S Send Message` | Text message |
| `E2S Send Email` | Email |

<details>
  <summary><strong>Show me how to build the shortcuts</strong></summary>

E2S hands each shortcut a small packet of text. `to` is the number or address, and `body` is the message text for messages and email.

**For `E2S Call`:**
1. Open **Shortcuts** and tap **+**.
2. Add **Get Dictionary from Input** (using *Shortcut Input*).
3. Add **Get Dictionary Value**, and set the key to `to`.
4. Add **Call** and choose the *Dictionary Value*.
5. Name the shortcut exactly `E2S Call`.

**For `E2S FaceTime` and `E2S FaceTime Audio`:** the same steps, but use the **FaceTime** action, set to video or audio.

**For `E2S Send Message` and `E2S Send Email`:** get both `to` and `body`, then use **Send Message** or **Send Email**. Turn off **Show When Run** or **Show Compose Sheet**, so they send without an extra screen.

E2S still reads everything back and **waits for the user to say yes** before anything is sent.

</details>

## Step 10: Siri and the Action Button {#step-10}

These let the user reach E2S without finding it on the screen.

{{< tabs >}}

{{< tab name="Action Button" icon="mdi:gesture-tap-button" >}}
On iPhones with an Action Button (iPhone 15 Pro and newer):
1. Open the iPhone's **Settings → Action Button**.
2. Swipe to **Shortcut** and choose **E2S → Talk to E2S**.
3. Now one press starts a voice conversation.
{{< /tab >}}

{{< tab name="Siri phrases" icon="mdi:microphone-message" >}}
- *"Talk to E2S"*: starts a conversation
- *"Ask E2S"*: asks one question
- *"Get directions with E2S"* and *"Stop E2S directions"*
- *"Describe with E2S"* and *"Read text with E2S"*
- *"Start E2S"* and *"Stop E2S"*: monitoring on or off
{{< /tab >}}

{{< tab name="Widgets" icon="mdi:widgets-outline" >}}
Long-press the Home Screen, tap **Edit → Add Widget**, and add E2S. It shows the next turn and running timers at a glance. These are handy for low-vision users, or for checking on someone's progress together.
{{< /tab >}}

{{< /tabs >}}

## Step 11: Privacy and Settings lock {#step-11}

Go to **Settings → Security, Privacy, & Camera**.

| Setting | What it does | Suggestion |
|---|---|---|
| **Lock Settings with Face ID or passcode** | Stops settings from being changed by tapping *or* by voice | Turn on once setup is done, if the user wants it |
| **Hide destination on Lock Screen** | Keeps where they're going private | On, for users who travel alone |
| **Hide E2S in the app switcher** | Blurs E2S when switching apps | The user's choice |
| **Apple street lookup** | Says the street name when asked "where am I?" by sending the location to Apple | On, if they want street names |
| **Floating indoor map** | Shows the mini-map after loading a saved scan | On for low vision, off for VoiceOver users |
| **Automatic camera descriptions** | Describes what the camera sees without being asked | Try it, then decide together |
| **Turn on the light when it's dark** | Uses the flashlight to help the camera | On |
| **Remember where I left off** | Lets E2S resume recipes and tasks | On |

> [!CAUTION]
> **Erase all E2S data** removes everything, including saved maps, recipes, keys and settings, and it **can't be undone**. Show the user where it is, but make sure they know what it does.

## Step 12: A quick tour of the app {#step-12}

Walk through each tab together:

{{< tabs >}}
  {{< tab name="Monitor" icon="mdi:waveform" >}}
  **Watches and listens around you.** Monitoring controls at the top, then modes like **Shopping**, then one card showing camera, sound and location status.
  {{< /tab >}}
  {{< tab name="Chat" icon="mdi:chat-outline" >}}
  **Talk with E2S.** Start a voice conversation, see what E2S has done, and read the conversation. **Clear conversation** sits right above the history.
  {{< /tab >}}
  {{< tab name="Tinker" icon="mdi:hammer-wrench" >}}
  **Get things done.** Timers, directions, and one card for typing or speaking requests, plus buttons to confirm, pause or cancel tasks.
  {{< /tab >}}
  {{< tab name="Settings" icon="mdi:cog-outline" >}}
  **Everything from this guide**, any time you need it.
  {{< /tab >}}
{{< /tabs >}}

## Step 13: Practice together {#step-13}

Try these phrases out loud, one at a time. **Wait for the listening vibration first!**

{{< tabs >}}
  {{< tab name="Basics" icon="mdi:star-outline" >}}
  - "What's the weather?"
  - "Repeat that."
  - "Stop speaking."
  - "Read my settings."
  {{< /tab >}}
  {{< tab name="Reading" icon="mdi:text-recognition" >}}
  - "Read this." Point the camera at a piece of mail.
  - "What's in front of me?"
  - Practice what **"Unsure"** means: that line needs a second check.
  {{< /tab >}}
  {{< tab name="Cooking" icon="mdi:chef-hat" >}}
  - "How do I make scrambled eggs?"
  - "Next step." / "Where was I?" / "Last step."
  - "Set a timer for 5 minutes."
  {{< /tab >}}
  {{< tab name="Getting around" icon="mdi:walk" >}}
  - "Take me to the nearest pharmacy."
  - "Load indoor scan Kitchen."
  - "Stop directions."
  {{< /tab >}}
{{< /tabs >}}

## Caretaker tips {#tips}

- **Start small.** Turn on two or three features first. Add more once those feel easy.
- **Keep the phone charged.** Camera and LiDAR use a lot of battery. A small battery pack is worth it for trips.
- **Check back in a week.** Ask what's annoying, too fast, too chatty or confusing, and adjust together.
- **Let them own it.** Once setup is done, the user can change almost anything by voice. That's on purpose!

<details>
  <summary><strong>Settings are locked and nobody remembers the passcode</strong></summary>

**Lock Settings** uses the iPhone's own Face ID or passcode. Whoever can unlock the iPhone can unlock E2S's settings.

</details>

<details>
  <summary><strong>E2S keeps hearing the TV or other people</strong></summary>

Turn on **noisy-place mode** and **ignore distant voices** in **Settings → Touch, Voice, & Haptics → Listening & voice focus**.

</details>

<details>
  <summary><strong>A shortcut says it "didn't finish"</strong></summary>

E2S must be **open on screen**, and the shortcut's name must match **exactly**, including spaces and capitals. For example, `E2S Call`, not `E2S call`.

</details>

<details>
  <summary><strong>Something isn't working or seems unsafe</strong></summary>

Email me at [467487@pm.me](mailto:467487@pm.me). Safety problems go straight to the top of my list.

</details>

{{< cta title="You're all set. Thank you for helping!" primary="Explore all features|/features/" secondary="Read the Terms of Use|/terms-of-use/" >}}
Questions about setup? Email [467487@pm.me](mailto:467487@pm.me). I read every message myself.
{{< /cta >}}

{{< /section >}}
