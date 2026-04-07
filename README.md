# Arena Model Unlocker

This is a browser extension that unlocks models on Arena AI and Canary Arena. It includes all Claude Opus models that were recently removed.

## What it does

The Arena AI uses a feature to hide Claude Opus models from the model selector. This extension stops that feature before the page loads and brings back every Opus model. It also unlocks over 150 hidden battle and test models.

### Supported sites

- [arena.ai](https://arena.ai)

- [canaryarena.ai](https://canaryarena.ai)

### Toggles

| Switch | What it does |

|--------|-------------|

| **** | Turns the extension on or off

| **Restore Opus** | Brings back all Claude Opus models

| **Show Hidden** Unlocks over 150 hidden models

## Install

1. [**Download the ZIP**](/opus-restorer.zip) or click **Code → Download ZIP** above

2. Extract the folder somewhere on your computer

3. Open your browser. Go to the extensions page

Chrome: `chrome://extensions`

Brave: `brave://extensions`

Edge: `edge://extensions`

4. Enable **Developer mode**

5. Click **Load * and select the extracted folder

6. Go to [arena.ai](https://arena.ai) or [canaryarena.ai](https://canaryarena.ai)

7. Click the extension icon. Make sure your toggles are on

8. Switch to **Direct** mode on Arena to pick models

9. **Reload the page** after changing any toggles

## Models restored

```

claude-opus-4-6              claude-opus-4-6-thinking       claude-opus-4-6-search

claude-opus-4-5-20251101     claude-opus-4-5-thinking-32k   claude-opus-4-5-search

claude-opus-4-1-20250805     claude-opus-4-1-thinking-16k   claude-opus-4-1-search

claude-opus-4-20250514       claude-opus-4-thinking-16k     claude-opus-4-search

```

## Hidden codenames discovered

Some models on Arena use codenames, for blind testing. With **Show Hidden** enabled you can find these:

Codename | Real model | Company |

|----------|-----------|---------|

| pteronura | Gemma 4 31B Google |

| significant-otter | Gemma 4 26B-A4B | Google |

deep-octo | MiniMax M2.7 | MiniMax |

| kiteki | Qwen 3.5 Max Preview | Alibaba |

| frieza | Longcat Flash Chat | Meituan |

tatertot | MAI Image 2 | Microsoft |

| arastradero Grok 4.20 Beta1 | xAI |

| flying-octopus | ??? | Unknown |

|. 140 More... | | |

## File structure

```

├── manifest.json     Extension info

├── boot.js           Settings loader

├── main.js           Data interceptor

├── popup.html        Popup UI

├── popup.js          Popup logic

├── icon.py           Icon generator

├── icon48.png        Icon

└── icon128.png       Icon

```

## Disclaimer

For research purposes only. This extension changes how the page looks. It does not change any server requests.

---

**Made by [RAKE](https://github.com/theraker526)**
