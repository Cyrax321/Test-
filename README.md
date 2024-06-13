<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Languages Used</title>
<style>
  body {
    font-family: -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica, Arial, sans-serif, Apple Color Emoji, Segoe UI Emoji;
    font-size: 14px;
    line-height: 21px;
  }
  
  .container {
    width: 360px;
    height: 210px;
    border: 1px solid rgb(225, 228, 232);
    border-radius: 6px;
    padding: 5px;
    box-sizing: border-box;
    background-color: white;
  }
  
  h2 {
    margin-top: 0;
    margin-bottom: 0.75em;
    line-height: 24px;
    font-size: 16px;
    font-weight: 600;
    color: rgb(36, 41, 46);
  }
  
  .progress {
    display: flex;
    height: 8px;
    overflow: hidden;
    background-color: rgb(225, 228, 232);
    border-radius: 6px;
    outline: 1px solid transparent;
    margin-bottom: 1em;
  }
  
  .progress-item {
    outline: 2px solid rgb(225, 228, 232);
    border-collapse: collapse;
  }
  
  .lang {
    font-weight: 600;
    margin-right: 4px;
    color: rgb(36, 41, 46);
  }
  
  .percent {
    color: rgb(88, 96, 105);
  }
  
  ul {
    list-style: none;
    padding-left: 0;
    margin-top: 0;
    margin-bottom: 0;
  }
  
  li {
    display: inline-flex;
    font-size: 12px;
    margin-right: 2ch;
    align-items: center;
    flex-wrap: nowrap;
    transform: translateX(-500%);
    animation-duration: 2s;
    animation-name: slideIn;
    animation-timing-function: ease-in-out;
    animation-fill-mode: forwards;
  }
  
  @keyframes slideIn {
    to {
      transform: translateX(0);
    }
  }
  
  .ellipsis {
    height: 100%;
    overflow: hidden;
    text-overflow: ellipsis;
  }
  
  .octicon {
    margin-right: 0.5ch;
    vertical-align: top;
  }
</style>
</head>
<body>
  <div class="container">
    <div class="ellipsis">
      <h2>Languages Used (By File Size)</h2>
      <div class="progress">
        <div style="background-color: #e34c26; width: 45.172%;" class="progress-item"></div>
        <div style="background-color: #f1e05a; width: 25.986%;" class="progress-item"></div>
        <div style="background-color: #563d7c; width: 9.656%;" class="progress-item"></div>
        <div style="background-color: #2b7489; width: 8.851%;" class="progress-item"></div>
        <div style="background-color: #00ADD8; width: 4.333%;" class="progress-item"></div>
        <div style="background-color: #427819; width: 2.016%;" class="progress-item"></div>
        <div style="background-color: #701516; width: 1.759%;" class="progress-item"></div>
        <div style="background-color: #ff3e00; width: 0.482%;" class="progress-item"></div>
        <div style="background-color: #b07219; width: 0.322%;" class="progress-item"></div>
        <div style="background-color: #c6538c; width: 0.265%;" class="progress-item"></div>
        <div style="background-color: #3572A5; width: 0.242%;" class="progress-item"></div>
        <div style="background-color: #2c3e50; width: 0.228%;" class="progress-item"></div>
        <div style="background-color: #a91e50; width: 0.173%;" class="progress-item"></div>
        <div style="background-color: #438eff; width: 0.130%;" class="progress-item"></div>
        <div style="background-color: #89e051; width: 0.129%;" class="progress-item"></div>
        <div style="background-color: #555555; width: 0.108%;" class="progress-item"></div>
        <div style="background-color: #f34b7d; width: 0.067%;" class="progress-item"></div>
        <div style="background-color: #ff6347; width: 0.023%;" class="progress-item"></div>
        <div style="background-color: #3D6117; width: 0.021%;" class="progress-item"></div>
        <div style="background-color: #da291c; width: 0.009%;" class="progress-item"></div>
        <div style="background-color: #384d54; width: 0.008%;" class="progress-item"></div>
        <div style="background-color: #4B6C4B; width: 0.005%;" class="progress-item"></div>
        <div style="background-color: #148AA8; width: 0.004%;" class="progress-item"></div>
        <div style="background-color: #DBCA00; width: 0.004%;" class="progress-item"></div>
        <div style="background-color: #101F1F; width: 0.003%;" class="progress-item"></div>
        <div style="background-color: #f7931e; width: 0.002%;" class="progress-item"></div>
        <div style="background-color: #000000; width: 0.002%;" class="progress-item"></div>
        <div style="background-color: #aa2afe; width: 0.000%;" class="progress-item"></div>
        <div style="background-color: #C1F12E; width: 0.000%;" class="progress-item"></div>
        <div style="background-color: #012456; width: 0.000%;" class="progress-item"></div>
        <div style="background-color: #1d365d; width: 0.000%;" class="progress-item"></div>
        <div style="background-color: #a53b70; width: 0.000%;" class="progress-item"></div>
      </div>
      <ul>
        <li style="animation-delay: 0ms;">
          <svg xmlns="http://www.w3.org/2000/svg" class="octicon" style="fill:#e34c26;" viewBox="0 0 16 16" version="1.1" width="16" height="16"><path fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z"></path></svg>
          <span class="lang">HTML</span>
          <span class="percent">45.17%</span>
        </li>
        <li style="animation-delay: 150ms;">
          <svg xmlns="http://www.w3.org/2000/svg" class="octicon" style="fill:#f1e05a;" viewBox="0 0 16 16" version="1.1" width="16" height="16"><path fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z"></path></svg>
          <span class="lang">JavaScript</span>
          <span class="percent">25.99%</span>
        </li>
        <li style="animation-delay: 300ms;">
          <svg xmlns="http://www.w3.org/2000/svg" class="octicon" style="fill:#563d7c;" viewBox="0 0 16 16" version="1.1" width="16" height="16"><path fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z"></path></svg>
          <span class="lang">CSS</span>
          <span class="percent">9.66%</span>
        </li>
        <li style="animation-delay: 450ms;">
          <svg xmlns="http://www.w3.org/2000/svg" class="octicon" style="fill:#2b7489;" viewBox="0 0 16 16" version="1.1" width="16" height="16"><path fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z"></path></svg>
          <span class="lang">TypeScript</span>
          <span class="percent">8.85%</span>
        </li>
        <li style="animation
        
