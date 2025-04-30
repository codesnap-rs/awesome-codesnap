# Awesome Codesnap [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
Collections of awesome codesnap configs, feel free to share your preferred configuration!

## How to use these configurations
1. Pick your preferred configuration
2. Replace your local configuration (If you are using CLI, the config file is located at `~/.config/CodeSnap/config.json`)
3. Run codesnap!

## Configurations

<details>
<summary>Mei</summary>

![image](https://github.com/user-attachments/assets/6533ef05-3f6b-423f-bc9e-3ce76c8c98a7)


```json
{
  "theme": "candy",
  "window": {
    "mac_window_bar": true,
    "shadow": {
      "radius": 20,
      "color": "#00000040"
    },
    "margin": {
      "x": 82,
      "y": 82
    },
    "border": {
      "width": 1,
      "color": "#ffffff30"
    },
    "title_config": {
      "color": "#ffffff",
      "font_family": "Pacifico"
    }
  },
  "code_config": {
    "font_family": "CaskaydiaCove Nerd Font",
    "breadcrumbs": {
      "separator": "/",
      "color": "#80848b",
      "font_family": "CaskaydiaCove Nerd Font"
    }
  },
  "watermark": {
    "content": "CodeSnap",
    "font_family": "Pacifico",
    "color": "#ffffff"
  },
  "background": {
    "start": {
      "x": 0,
      "y": 0
    },
    "end": {
      "x": "max",
      "y": "max"
    },
    "stops": [
      {
        "position": 0,
        "color": "#EBECB2"
      },
      {
        "position": 0.28,
        "color": "#F3B0F7"
      },
      {
        "position": 0.73,
        "color": "#92B5F0"
      },
      {
        "position": 0.94,
        "color": "#AEF0F8"
      }
    ]
  },
  "line_number_color": "#D3D3D3"
}
```

</details>

<details>
<summary>Vercel</summary>
  
  ![image](https://github.com/user-attachments/assets/008cfc06-143b-44f3-b2a2-96b73e38e4b2)

  
  ```json
  {
  "print_eggs": false,
  "snapshot_config": {
    "theme": "vercel@https://raw.githubusercontent.com/Railly/one-hunter-vscode/refs/heads/main/themes/OneHunter-Vercel-color-theme.json",
    "window": {
      "mac_window_bar": true,
      "shadow": {
        "radius": 20,
        "color": "#00000040"
      },
      "margin": {
        "x": 82,
        "y": 82
      },
      "border": {
        "width": 1,
        "color": "#ffffff30"
      },
      "title_config": {
        "color": "#ffffff",
        "font_family": "Pacifico"
      }
    },
    "code_config": {
      "font_family": "CaskaydiaCove Nerd Font",
      "breadcrumbs": {
        "separator": "/",
        "color": "#80848b",
        "font_family": "CaskaydiaCove Nerd Font"
      }
    },
    "watermark": {
      "content": "CodeSnap",
      "font_family": "Pacifico",
      "color": "#ffffff"
    },
    "background": {
      "start": {
        "x": 0,
        "y": 0
      },
      "end": {
        "x": "max",
        "y": "max"
      },
      "stops": [
        {
          "position": 0,
          "color": "#0A0A0A"
        },
        {
          "position": 0.94,
          "color": "#000000"
        }
      ]
    },
    "line_number_color": "#D3D3D3"
  }
}
  ```
</details>

