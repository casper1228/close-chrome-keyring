#!/bin/bash

AUTOSTART="$HOME/.config/autostart/google-chrome.desktop"

if [ -f "$AUTOSTART" ]; then
  sed -i 's|Exec=.*|Exec=/usr/bin/google-chrome-stable --password-store=basic|' "$AUTOSTART"
  echo "[✓] Chrome autostart updated."
else
  echo "[!] $AUTOSTART not found."
fi
