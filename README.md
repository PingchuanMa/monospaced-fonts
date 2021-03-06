# Monospaced / Programming / Fixed-width Fonts

All fonts are collected from the Internet.

## Getting Started

```sh
curl -L https://github.com/PingchuanMa/monospaced-fonts/raw/main/install.sh | bash
```

## Usage

- Ubuntu Terminal:

    Go to `Preferences/Profiles/name-of-your-profile` , check `Custom font` box, and select `Monaco Powerline Regular` .

- Visual Studio Code:

    ```json
    "editor.fontFamily": "'Monaco'"
    ```

- Overleaf:

    Select `Monaco` in left sidebar.

- GitHub (Chrome):

    Install [Stylus](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) and create a style for `github.com` :
    
    ```css
    .line-data,
    #gist-form .file .input textarea,
    .blob-code-inner {
        font-family: "Monaco"
    }

    code,
    pre {
        font-family: "Monaco"
    }
    ```

- More usage examples are welcomed.

## Acknowledgement

- `Monaco_Linux-Powerline.ttf` : [[Source]](https://gist.github.com/epegzz/1634235#file-monaco_linux-powerline-ttf)
- `monaco.ttf` : [[Source]](https://github.com/todylu/monaco.ttf/blob/master/monaco.ttf)
