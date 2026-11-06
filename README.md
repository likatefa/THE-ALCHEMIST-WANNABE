<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Alchemist — Private Access</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,300;0,9..144,500;0,9..144,600;1,9..144,400&family=IBM+Plex+Sans:wght@300;400;500;600&family=IBM+Plex+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
  :root{
    --bg:#0a0a0b;
    --bg-raised:#131315;
    --ink:#e9e5dd;
    --ink-dim:#a8a39a;
    --steel:#8b9096;
    --blood:#7d2323;
    --blood-bright:#a63131;
    --line: rgba(233,229,221,0.14);
    --serif: 'Fraunces', serif;
    --sans: 'IBM Plex Sans', sans-serif;
    --mono: 'IBM Plex Mono', monospace;
    padding-top: env(safe-area-inset-top, 0px);
    padding-bottom: env(safe-area-inset-bottom, 0px);
    box-sizing: border-box;
  }
  *{box-sizing:border-box;}
  html{scroll-padding-top: env(safe-area-inset-top, 0px); scroll-behavior:smooth;}
  html,body{height:100%;}
  body{
    margin:0;
    background:var(--bg);
    color:var(--ink);
    font-family:var(--sans);
    font-weight:300;
    line-height:1.6;
    overflow-x:hidden;
  }
  ::selection{background:var(--blood); color:#fff;}
