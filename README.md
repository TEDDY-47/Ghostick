# Ghostick

A single-page controller tester that runs in your browser. No install, no backend, no dependencies.

**Live demo:** https://teddy-47.github.io/Ghostick/

## Features

- **Virtual controller**: every button lights up while pressed and glows green once tested, with a live tested counter
- **Analog triggers**: LT and RT fill up as you pull them, so you can check smooth travel
- **Stick drift test**: leave both sticks idle for 5 seconds and get an average and peak drift percentage with a verdict (Clean, Minor drift, Drifting)
- **Adjustable deadzone**: see whether your drift would actually show up in games
- **Rumble test**: strong motor, weak motor, both, and pulse
- **Up to 4 controllers**: switch between connected pads from the slots at the top
- **Auto labels**: Xbox, PlayStation and Switch Pro layouts get the right button names
- **Light and dark theme**: follows your device setting

## How to use

1. Open the page in Chrome or Edge.
2. Connect your controller (USB, Bluetooth or wireless adapter).
3. Press any button so the browser detects it.
4. Press every button and pull both triggers until the counter reaches the total.
5. Leave the sticks alone and tap **Start 5s test**.

## Drift scale

| Average drift | Verdict |
|---------------|---------|
| Under 3% | Clean |
| 3% to 8% | Minor drift |
| Over 8% | Drifting |

## Browser support

Uses the standard [Gamepad API](https://developer.mozilla.org/docs/Web/API/Gamepad_API).

- Chrome and Edge: full support, including rumble
- Firefox and Safari: buttons and sticks work, rumble is not supported

## Host it yourself

1. Fork or upload this repo to your GitHub account.
2. Go to **Settings > Pages**.
3. Set the source to the `main` branch, root folder.
4. Your page will be live at `https://<username>.github.io/<repo>/`.

It is one `index.html` file, so you can also just open it locally.

## License

[MIT](LICENSE)
