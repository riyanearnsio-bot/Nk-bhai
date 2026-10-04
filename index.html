<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover, maximum-scale=1.0, user-scalable=no">
  <title>OB 55 PROXY SERVER — Install</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;500;600;700;800&family=Space+Mono:wght@400;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg: #080c0a;
      --surface: #0f1612;
      --glass: rgba(15, 22, 18, 0.78);
      --line: rgba(180, 255, 200, 0.07);
      --primary: #2ef2a8;
      --secondary: #ff7a18;
      --tertiary: #b44aff;
      --gold: #ffe066;
      --text: #edfbf3;
      --muted: #7a9488;
      --font: 'Outfit', sans-serif;
      --mono: 'Space Mono', monospace;
    }

    *, *::before, *::after {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      -webkit-tap-highlight-color: transparent;
    }

    body {
      font-family: var(--font);
      background: var(--bg);
      color: var(--text);
      min-height: 100vh;
      min-height: 100dvh;
      overflow-x: hidden;
      -webkit-font-smoothing: antialiased;
      padding-bottom: env(safe-area-inset-bottom, 0px);
    }

    body::before {
      content: '';
      position: fixed;
      inset: 0;
      background:
        radial-gradient(ellipse 80% 50% at 20% -10%, rgba(46, 242, 168, 0.11), transparent),
        radial-gradient(ellipse 60% 40% at 90% 20%, rgba(255, 122, 24, 0.1), transparent),
        radial-gradient(ellipse 50% 30% at 50% 100%, rgba(180, 74, 255, 0.08), transparent);
      pointer-events: none;
      z-index: 0;
    }

    .grid-bg {
      position: fixed;
      inset: 0;
      background-image:
        linear-gradient(rgba(46, 242, 168, 0.04) 1px, transparent 1px),
        linear-gradient(90deg, rgba(46, 242, 168, 0.04) 1px, transparent 1px);
      background-size: 48px 48px;
      mask-image: radial-gradient(ellipse 70% 60% at 50% 40%, black, transparent);
      pointer-events: none;
      z-index: 0;
    }

    header {
      position: sticky;
      top: 0;
      z-index: 100;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 14px 20px;
      background: var(--glass);
      backdrop-filter: blur(18px);
      -webkit-backdrop-filter: blur(18px);
      border-bottom: 1px solid var(--line);
    }

    .brand {
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .brand-logo {
      width: 34px;
      height: 34px;
      border-radius: 9px;
      object-fit: cover;
      flex-shrink: 0;
      border: 1px solid rgba(255, 224, 102, 0.35);
      box-shadow: 0 3px 14px rgba(255, 180, 40, 0.18);
    }

    .brand h1 {
      font-size: 15px;
      font-weight: 700;
      letter-spacing: 0.04em;
      text-transform: uppercase;
    }

    .live-badge {
      display: flex;
      align-items: center;
      gap: 6px;
      font-family: var(--mono);
      font-size: 10px;
      font-weight: 700;
      letter-spacing: 0.12em;
      color: var(--primary);
      padding: 6px 12px;
      border: 1px solid rgba(46, 242, 168, 0.35);
      border-radius: 20px;
      background: rgba(46, 242, 168, 0.07);
    }

    .live-dot {
      width: 7px;
      height: 7px;
      border-radius: 50%;
      background: var(--primary);
      box-shadow: 0 0 8px var(--primary);
      animation: pulse 1.4s ease-in-out infinite;
    }

    @keyframes pulse {
      0%, 100% { opacity: 1; transform: scale(1); }
      50% { opacity: 0.5; transform: scale(0.85); }
    }

    .ticker-wrap {
      position: relative;
      z-index: 1;
      overflow: hidden;
      border-bottom: 1px solid var(--line);
      background: rgba(0, 0, 0, 0.35);
      padding: 8px 0;
    }

    .ticker-track {
      display: flex;
      gap: 32px;
      white-space: nowrap;
      animation: scroll 28s linear infinite;
      font-size: 12px;
      color: var(--muted);
    }

    .ticker-track span.highlight {
      color: var(--secondary);
      font-weight: 600;
    }

    @keyframes scroll {
      0% { transform: translateX(0); }
      100% { transform: translateX(-50%); }
    }

    .page {
      position: relative;
      z-index: 1;
      max-width: 1100px;
      margin: 0 auto;
      padding: 16px 14px 12px;
    }

    @media (min-width: 768px) {
      .page {
        padding: 24px 16px 40px;
      }
    }

    .section-tag {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      font-family: var(--mono);
      font-size: 10px;
      font-weight: 700;
      letter-spacing: 0.14em;
      color: var(--muted);
      margin-bottom: 10px;
    }

    @media (min-width: 768px) {
      .section-tag {
        font-size: 11px;
        margin-bottom: 14px;
      }
    }

    .section-tag::before {
      content: '';
      width: 18px;
      height: 2px;
      background: linear-gradient(90deg, var(--primary), var(--secondary));
    }

    .split {
      display: grid;
      grid-template-columns: 1fr;
      gap: 0;
      align-items: start;
    }

    .right-col {
      display: flex;
      flex-direction: column;
      gap: 0;
    }

    @media (min-width: 768px) {
      .split {
        grid-template-columns: 1.15fr 0.85fr;
        gap: 28px;
        align-items: start;
      }

      .right-col {
        gap: 16px;
      }
    }

    .video-panel {
      position: relative;
    }

    .video-frame { position: relative;
      position: relative;
      border-radius: 16px;
      overflow: hidden;
      background: var(--surface);
      border: 1px solid var(--line);
      box-shadow:
        0 0 0 1px rgba(46, 242, 168, 0.06),
        0 12px 40px rgba(0, 0, 0, 0.5),
        0 0 60px rgba(255, 122, 24, 0.06);
    }

    @media (min-width: 768px) {
      .video-frame {
        border-radius: 20px;
        box-shadow:
          0 0 0 1px rgba(46, 242, 168, 0.06),
          0 20px 60px rgba(0, 0, 0, 0.6),
          0 0 80px rgba(255, 122, 24, 0.08);
      }
    }

    .video-frame::before,
    .video-frame::after {
      content: '';
      position: absolute;
      width: 28px;
      height: 28px;
      border: 2px solid var(--primary);
      z-index: 2;
      pointer-events: none;
      opacity: 0.7;
    }

    .video-frame::before {
      top: 12px;
      left: 12px;
      border-right: none;
      border-bottom: none;
      border-radius: 4px 0 0 0;
    }

    .video-frame::after {
      bottom: 12px;
      right: 12px;
      border-left: none;
      border-top: none;
      border-radius: 0 0 4px 0;
    }

    .video-frame .main-media {
      width: 100%;
      height: auto;
      display: block;
      background: #000;
      user-select: none;
      -webkit-user-drag: none;
    }

    .video-label {
      position: absolute;
      top: 14px;
      right: 14px;
      z-index: 3;
      font-family: var(--mono);
      font-size: 10px;
      font-weight: 700;
      letter-spacing: 0.1em;
      padding: 5px 10px;
      border-radius: 6px;
      background: rgba(0, 0, 0, 0.65);
      border: 1px solid rgba(229, 57, 53, 0.45);
      color: #ff4444;
    }

    .video-label .live-dot-label {
      display: inline-block;
      width: 6px;
      height: 6px;
      border-radius: 50%;
      background: #ff4444;
      margin-right: 5px;
      vertical-align: middle;
      box-shadow: 0 0 6px #ff4444;
      animation: pulse 1.4s ease-in-out infinite;
    }

    .step-bridge {
      text-align: center;
      padding: 14px 0 12px;
    }

    .bridge-title {
      font-size: 17px;
      font-weight: 800;
      letter-spacing: 0.04em;
      text-transform: uppercase;
      line-height: 1.2;
      background: linear-gradient(135deg, #fff 20%, var(--secondary) 70%, var(--primary));
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      margin-bottom: 4px;
    }

    .bridge-sub {
      display: none;
    }

    .install-stat {
      text-align: center;
      font-size: 11px;
      color: var(--muted);
      margin-bottom: 10px;
    }

    .install-stat strong {
      color: var(--primary);
      font-weight: 700;
    }


    .last-hour-label { font-size: 11px; font-weight: 500; letter-spacing: .02em; }
    .install-wrap {
      max-width: 360px;
      margin: 0 auto;
    }

    @media (min-width: 768px) {
      .step-bridge {
        padding: 8px 0 4px;
      }

      .bridge-title {
        font-size: 20px;
      }
    }

    .live-chat {
      margin-top: 16px;
      padding: 16px;
      border-radius: 16px;
      background: var(--glass);
      backdrop-filter: blur(20px);
      -webkit-backdrop-filter: blur(20px);
      border: 1px solid var(--line);
    }

    @media (min-width: 768px) {
      .live-chat {
        margin-top: 28px;
        padding: 20px;
        border-radius: 20px;
      }
    }

    .live-chat-header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      margin-bottom: 12px;
    }

    .live-chat-title {
      display: flex;
      align-items: center;
      gap: 8px;
      font-family: var(--mono);
      font-size: 11px;
      font-weight: 700;
      letter-spacing: 0.12em;
      color: var(--text);
    }

    .live-dot-chat {
      width: 7px;
      height: 7px;
      border-radius: 50%;
      background: #ff4444;
      box-shadow: 0 0 8px #ff4444;
      animation: pulse 1.4s ease-in-out infinite;
    }

    .comment-count {
      font-family: var(--mono);
      font-size: 10px;
      color: var(--muted);
      font-weight: 700;
      letter-spacing: 0.06em;
    }

    .comments-scroll {
      min-height: 200px;
      max-height: 240px;
      overflow-y: auto;
      overflow-x: hidden;
      display: flex;
      flex-direction: column;
      gap: 12px;
      padding-right: 4px;
      padding-bottom: 8px;
      scroll-behavior: smooth;
    }

    @media (max-width: 767px) {
      .comments-scroll {
        mask-image: linear-gradient(to bottom, #000 0%, #000 72%, transparent 100%);
        -webkit-mask-image: linear-gradient(to bottom, #000 0%, #000 72%, transparent 100%);
      }
    }

    @media (min-width: 768px) {
      .comments-scroll {
        min-height: 240px;
        max-height: 300px;
        gap: 12px;
      }
    }

    .scroll-hint {
      display: none;
    }

    @media (max-width: 767px) {
      .scroll-hint {
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 4px;
        margin-top: 8px;
        font-family: var(--mono);
        font-size: 9px;
        font-weight: 700;
        letter-spacing: 0.1em;
        color: var(--muted);
        opacity: 0.85;
        animation: hintBounce 2s ease-in-out infinite;
      }

      .scroll-hint svg {
        width: 12px;
        height: 12px;
        fill: var(--muted);
      }

      @keyframes hintBounce {
        0%, 100% { transform: translateY(0); opacity: 0.7; }
        50% { transform: translateY(3px); opacity: 1; }
      }
    }

    .comments-scroll::-webkit-scrollbar {
      width: 3px;
    }

    .comments-scroll::-webkit-scrollbar-thumb {
      background: rgba(46, 242, 168, 0.25);
      border-radius: 3px;
    }

    .comment {
      display: flex;
      gap: 10px;
      animation: commentPop 0.25s ease;
    }

    @keyframes commentPop {
      from { opacity: 0; transform: translateY(6px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .comment-avatar {
      width: 32px;
      height: 32px;
      border-radius: 50%;
      flex-shrink: 0;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 12px;
      font-weight: 700;
      color: #fff;
    }

    .comment-body {
      flex: 1;
      min-width: 0;
    }

    .comment-meta {
      display: flex;
      align-items: baseline;
      gap: 8px;
      margin-bottom: 3px;
    }

    .comment-name {
      font-size: 12px;
      font-weight: 700;
      color: var(--text);
    }

    .comment-time {
      font-family: var(--mono);
      font-size: 10px;
      color: var(--muted);
    }

    .comment-text {
      font-size: 12px;
      color: #b8cfc4;
      line-height: 1.4;
      word-break: break-word;
    }

    .typing-bar {
      display: flex;
      align-items: center;
      gap: 8px;
      padding: 8px 0 2px;
      min-height: 28px;
    }

    .typing-avatar {
      width: 24px;
      height: 24px;
      border-radius: 50%;
      background: rgba(255, 255, 255, 0.08);
      flex-shrink: 0;
    }

    .typing-dots {
      display: flex;
      gap: 4px;
      padding: 6px 12px;
      background: rgba(255, 255, 255, 0.05);
      border: 1px solid var(--line);
      border-radius: 14px;
    }

    .typing-dots span {
      width: 5px;
      height: 5px;
      border-radius: 50%;
      background: var(--muted);
      animation: typeDot 1s ease-in-out infinite;
    }

    .typing-dots span:nth-child(2) { animation-delay: 0.15s; }
    .typing-dots span:nth-child(3) { animation-delay: 0.3s; }

    @keyframes typeDot {
      0%, 100% { opacity: 0.3; transform: translateY(0); }
      50% { opacity: 1; transform: translateY(-3px); }
    }

    .typing-bar.hidden {
      display: none;
    }

    .offer-card {
      position: relative;
      padding: 14px;
      border-radius: 16px;
      background: var(--glass);
      backdrop-filter: blur(20px);
      -webkit-backdrop-filter: blur(20px);
      border: 1px solid var(--line);
      overflow: hidden;
    }

    @media (min-width: 768px) {
      .offer-card {
        padding: 24px;
        border-radius: 24px;
      }
    }

    .offer-card::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      height: 3px;
      background: linear-gradient(90deg, var(--secondary), var(--primary), var(--tertiary));
    }

    .offer-card::after {
      content: '';
      position: absolute;
      top: -60px;
      right: -60px;
      width: 160px;
      height: 160px;
      border-radius: 50%;
      background: radial-gradient(circle, rgba(180, 74, 255, 0.14), transparent 70%);
      pointer-events: none;
    }

    .icon-wrap {
      display: flex;
      justify-content: center;
      margin-bottom: 0;
    }

    .offer-card-inner { display: flex; align-items: center; gap: 16px; }

    .offer-card-body {
      flex: 1;
      min-width: 0;
    }

    .app-icon { width: 76px; height: 76px; border-radius: 18px;
      object-fit: cover;
      border: 2px solid rgba(46, 242, 168, 0.35);
      box-shadow: 0 4px 16px rgba(46, 242, 168, 0.15);
      flex-shrink: 0;
    }

    @media (min-width: 768px) {
      .icon-wrap {
        margin-bottom: 18px;
      }

      .offer-card-inner {
        display: block;
      }

      .app-icon { width: 96px; height: 96px;
        border-radius: 22px;
        box-shadow: 0 8px 32px rgba(46, 242, 168, 0.18);
      }
    }

    .tag-row {
      display: flex;
      justify-content: flex-start;
      gap: 6px;
      margin-bottom: 4px;
      flex-wrap: wrap;
    }

    @media (min-width: 768px) {
      .tag-row {
        justify-content: center;
        gap: 8px;
        margin-bottom: 12px;
      }
    }

    .tag {
      font-size: 10px;
      font-weight: 700;
      letter-spacing: 0.08em;
      text-transform: uppercase;
      padding: 4px 10px;
      border-radius: 20px;
    }

    .tag-hot {
      background: rgba(255, 122, 24, 0.15);
      color: var(--secondary);
      border: 1px solid rgba(255, 122, 24, 0.35);
    }

    .tag-pro {
      background: rgba(180, 74, 255, 0.14);
      color: #d896ff;
      border: 1px solid rgba(180, 74, 255, 0.35);
    }

    .offer-title { text-align: left; font-size: 20px;
      font-weight: 800;
      margin-bottom: 2px;
    }

    .offer-desc { text-align: left; font-size: 12px;
      color: var(--muted);
      line-height: 1.35;
      margin-bottom: 0;
    }

    .rating {
      display: flex;
      align-items: center;
      justify-content: flex-start;
      gap: 6px;
      margin-top: 4px;
      margin-bottom: 0;
      font-size: 12px;
      font-weight: 600;
    }

    @media (min-width: 768px) {
      .offer-title { text-align: center; font-size: 24px;
        margin-bottom: 6px;
      }

      .offer-desc {
        text-align: center;
        font-size: 13px;
        line-height: 1.5;
        margin-bottom: 18px;
      }

      .rating {
        justify-content: center;
        margin-top: 0;
        margin-bottom: 18px;
        font-size: 14px;
      }
    }

    .rating .stars {
      color: var(--gold);
      letter-spacing: 2px;
    }

    .chips {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 6px;
      margin-top: 12px;
      margin-bottom: 0;
    }

    @media (min-width: 768px) {
      .chips {
        gap: 8px;
        margin-top: 0;
        margin-bottom: 20px;
      }
    }

    .chip {
      text-align: center;
      padding: 7px 4px;
      border-radius: 10px;
      background: rgba(255, 255, 255, 0.03);
      border: 1px solid var(--line);
    }

    .chip strong {
      display: block;
      font-size: 11px;
      font-weight: 700;
      color: var(--primary);
      margin-bottom: 1px;
    }

    .chip span {
      font-size: 9px;
      color: var(--muted);
      text-transform: uppercase;
      letter-spacing: 0.06em;
    }

    @media (min-width: 768px) {
      .chip {
        padding: 10px 6px;
        border-radius: 12px;
      }

      .chip strong {
        font-size: 13px;
        margin-bottom: 2px;
      }

      .chip span {
        font-size: 10px;
      }
    }

    .install-btn {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 10px;
      width: 100%;
      padding: 14px 20px;
      border: none;
      border-radius: 14px;
      font-family: var(--font);
      font-size: 15px;
      font-weight: 700;
      letter-spacing: 0.04em;
      text-transform: uppercase;
      color: #fff;
      text-decoration: none;
      cursor: pointer;
      position: relative;
      overflow: hidden;
      background: linear-gradient(135deg, var(--secondary) 0%, var(--primary) 45%, var(--tertiary) 100%);
      box-shadow: 0 8px 30px rgba(255, 122, 24, 0.28);
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }

    @media (min-width: 768px) {
      .install-btn {
        padding: 16px 24px;
        border-radius: 16px;
        font-size: 16px;
      }
    }

    .install-btn::before {
      content: '';
      position: absolute;
      inset: 0;
      background: linear-gradient(105deg, transparent 40%, rgba(255,255,255,0.2) 50%, transparent 60%);
      transform: translateX(-100%);
      animation: shimmer 3s ease-in-out infinite;
    }

    @keyframes shimmer {
      0%, 100% { transform: translateX(-100%); }
      50% { transform: translateX(100%); }
    }

    .install-btn:hover {
      transform: translateY(-1px);
      box-shadow: 0 12px 40px rgba(46, 242, 168, 0.3);
    }

    .install-btn:active {
      transform: scale(0.98);
    }

    .install-btn svg {
      width: 20px;
      height: 20px;
      fill: currentColor;
      flex-shrink: 0;
    }

    .trust-row {
      display: none;
    }

    @media (min-width: 768px) {
      .trust-row {
        display: flex;
        justify-content: center;
        gap: 20px;
        margin-top: 28px;
        padding-top: 20px;
        border-top: 1px solid var(--line);
        flex-wrap: wrap;
      }
    }

    .trust-item {
      display: flex;
      align-items: center;
      gap: 6px;
      font-size: 11px;
      color: var(--muted);
    }

    .trust-item svg {
      width: 16px;
      height: 16px;
      fill: var(--primary);
      opacity: 0.8;
    }

    .trust-item strong {
      color: var(--text);
    }

    footer {
      position: relative;
      z-index: 1;
      text-align: center;
      padding: 8px 16px 10px;
      font-size: 10px;
      color: var(--muted);
      border-top: 1px solid var(--line);
    }

    @m
