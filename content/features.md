---
description: "E2S - Features and Capabilities"
date: 2026-10-18
draft: false
layout: "landing"
---
<style>
  h2[id], h3[id] { scroll-margin-top: 6.5rem; }
  @media (prefers-reduced-motion: no-preference) {
    html { scroll-behavior: smooth; }
  }
.card.card--linked {
  position: relative;
  isolation: isolate;
}

.card.card--linked > a.card__link {
  position: absolute;
  inset: 0;
  z-index: 1;
  display: block;
  border-radius: inherit;
  cursor: pointer;
}

.card.card--linked > a.card__link:focus-visible {
  outline: 3px solid var(--color-accent, #22d3ee);
  outline-offset: 4px;
}

@media (prefers-reduced-motion: reduce) {
  .card.card--linked {
    transition: none;
  }

  .card.card--linked:hover {
    transform: none;
  }
}
</style>

{{< hero title="Do more with" titleAccent="E2S Assistant." subtitle="A personal assistant for blind, low-vision and disabled people. Use your voice or touch, whichever you prefer. **Free. Open source. Forever.**" >}}

{{< pills >}}
  {{< pill icon="mdi:microphone-outline" >}}Voice or touch{{< /pill >}}
  {{< pill icon="mdi:cellphone-check" >}}Works on your iPhone{{< /pill >}}
  {{< pill icon="mdi:shield-lock-outline" >}}Private by design{{< /pill >}}
  {{< pill icon="mdi:vibrate" >}}Haptic feedback{{< /pill >}}
{{< /pills >}}

{{< buttons >}}
  {{< button href="[APP STORE LINK]" variant="primary" size="lg" icon="simple-icons:apple" >}}Get E2S{{< /button >}}
  {{< button href="https://github.com/ooofruitsnacks/E2S" target="_blank" variant="ghost" size="lg" icon="mdi:github" >}}View the code{{< /button >}}
{{< /buttons >}}

{{< /hero >}}

{{< section width="narrow" >}}

## Jump to a feature

{{< feature-grid >}}
  {{< feature-card title="Getting around" icon="mdi:map-marker-path" url="/features/#getting-around" >}}
  Walking directions, transit, nearby places, and Path Alerts.
  {{< /feature-card >}}
  {{< feature-card title="Indoor guidance" icon="mdi:cube-scan" url="/features/#indoor-guidance" >}}
  Scan rooms with LiDAR, save them, and load them by name.
  {{< /feature-card >}}
  {{< feature-card title="Seeing & reading" icon="mdi:eye-outline" url="/features/#seeing-and-reading" >}}
  Read text, find signs and objects, and hear what's around you.
  {{< /feature-card >}}
  {{< feature-card title="Food & shopping" icon="mdi:cart-outline" url="/features/#food-and-shopping" >}}
  Grocery lists, barcode checks, allergens, recipes, and timers.
  {{< /feature-card >}}
  {{< feature-card title="Everyday help" icon="mdi:tshirt-crew-outline" url="/features/#everyday-help" >}}
  Getting dressed, calls, messages, weather, books, and more.
  {{< /feature-card >}}
  {{< feature-card title="Make it yours" icon="mdi:tune-variant" url="/features/#make-it-yours" >}}
  Voice, vibration patterns, privacy, and caretaker tools.
  {{< /feature-card >}}
{{< /feature-grid >}}

{{< /section >}}

{{< section width="narrow" >}}

## Monitoring Modes For Any Situation

{{< tabs >}}
  {{< tab name="Monitor" icon="mdi:waveform" >}}
  Watches and listens around you. Turn on camera narration, sound alerts, and monitoring modes like **Shopping**. Camera, sound and location status are all in one place.
  {{< /tab >}}
  {{< tab name="Chat" icon="mdi:chat-outline" >}}
  Talk with E2S. Your conversation, directions and Path Alerts appear here, along with evidence and receipts for the tasks E2S has done.
  {{< /tab >}}
  {{< tab name="Public Spaces" icon="mdi:account-multiple-plus-outline" >}}
  Going out? Turn on this mode for optimal warnings about groups of people, fences, stairs, or any other obstacles typically found in public spaces.
  {{< /tab >}}
  {{< tab name="Store/Shopping" icon="mdi:cart" >}}
  Tailored towards grocery stores, malls, or other large shopping areas to warn the user of shopping carts, aisles, stacked items, etc. This mode helps the user navigate around a store.
  {{< /tab >}}
{{< /tabs >}}

<h2 id=environmental-monitoring"<Environmental Monitoring</h2>

__E2S Assistant__ is designed to provide the user with accurate environment descriptions and guidance. __E2S Assistant__ warns the user of obstacles or objects in their path, people or animals, or hazards that could pose danger to the user. E2S utilizes LiDAR to also help with elevation changes or stairs. E2S will monitor background noises for things like sirens, EV cars, or truck reverse noises.

<h2 id="getting-around">Getting Around</h2>

- **Walking directions** with spoken turns and vibration cues
- **Path Alerts** that warn about obstacles ahead, using the camera and LiDAR
- **Transit planning** for buses and trains
- **Nearby search** that picks the place you meant, not just the first result
- **Compass** to check which way you're facing
- **Home Screen widget** that shows your next turn at a glance

> [!WARNING]
> Directions and Path Alerts are helpers, not guarantees. Keep using your cane, guide dog, and training. Read the [Terms of Use](/terms-of-use/).

<h2 id="outdoor-navigation">Outdoor Navigation</h2>

- **Path Alerts** configure your settings for different warning distances
- **Route Settings** choose between walking, cycling, driving or public transit routes
- **Map Settings** choose between Apple Maps, outdoors with trails, countour lines, hiking, cycling, subway and rail maps
- **Route Guidance Customizaiton** the user has full control over route line color and thickness, spoken directions, haptic cues and more
- **Maps and Widgets** E2S has an in app floating tile with support for widgets and live activities notifications so you never miss a direction

<h2 id="indoor-guidance">Indoor Guidance</h2>

- **Indoor Scanning** with the iPhone's LiDAR sensor
- **Saved Maps Library** Name your scans then just say *"Load indoor scan Kitchen."*
- **Find Me** works out where you are in a saved room
- **Room guide** walks you to places inside a mapped room
- **Floating map tile** that appears when you load a saved scan
- **Scan recovery** saves your progress if the app closes partway through a scan
- **Store Mapping** *(development preview)*: early tools for mapping stores

<h2 id="seeing-and-reading">Seeing and Reading</h2>

- **Text reader** for labels, mail and signs. When a line is hard to read, E2S says it's **unsure** instead of guessing.
- **Closer look**: on iPhones with Apple Intelligence, E2S takes a second look at hard-to-read lines
- **Sign finder** and **object finder**
- **Scene descriptions** of what's in front of you
- **Hand and finger guidance** that helps you reach what the camera sees
- **Night vision** to help the camera in low light
- **Sound alerts** for sirens, horns, backup beeps, and more

<h2 id="food-and-shopping">Food and Nutrition</h2>

- **Grocery lists** managed by voice controls
- **Barcode scanning** check products ingredients using Open Food Facts and receive food ratings
- **Allergy and diet profile** E2S warns you about ingredients or other diet restrictions for recipes or scanned barcodes
- **Recipes**: search, save, edit, and cook **step by step**. Say *"next step," "where was I,"* or *"last step."*
- **Step timers** for cooking with alarms including Live Activities

<h2 id="everyday-help">Everyday Help</h2>

- **Getting dressed**: help with clothes and outfits
- **Calls and messages**, read back to you before anything is sent
- **Weather** for where you are, or any city
- **Web search** using your own Brave Search key
- **Talking books**
- **Siri and Shortcuts** support
- **Memory**: E2S can remember things you tell it

<h2 id="make-it-yours">Make It Yours</h2>

- **Voice settings**: choose the voice, speed and style
- **Custom vibration patterns** for different alerts
- **Pocket mode** for when your phone's in your pocket
- **Battery-aware** features that ease off when the battery is low
- **Lock Settings with Face ID**, which caretakers find handy
- **Erase all E2S data** with one button

<details>
  <summary><strong>Does E2S cost anything?</strong></summary>

No. E2S is free, with no ads, subscriptions or in-app purchases.

</details>

<details>
  <summary><strong>Does E2S need an internet connection?</strong></summary>

Many features work right on your iPhone. Maps, transit, product lookups, weather and web search need a connection.

</details>

<details>
  <summary><strong>Where is my data stored?</strong></summary>

On your iPhone. Read the [Privacy Policy](/privacy-policy/) for details.

</details>

{{< cta title="Ready to do more?" primary="Get E2S|[APP STORE LINK]" secondary="Read the docs|/" >}}
Free. Open source. Forever. Made with care by Owen.
{{< /cta >}}

{{< /section >}}
