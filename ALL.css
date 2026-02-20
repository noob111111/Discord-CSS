/* HIDE TOP BAR */
@import url('https://raw.githubusercontent.com/G0d0fninjas/visual-refresh-compact-title-bar/refs/heads/experimental/desktop.css');
@import url("https://raw.githubusercontent.com/scattagain/VencordStuff/4fa465629d6d71092c20aa11245abb6ad4a44641/css/GuildbarRevert.css");
/* SEARCH BAR MARGIN */
.searchBar__97492 {
  margin-right: 75px;
}
/* GROUP DM MARGIN */
.inviteToolbar__133bf, .toolbar__9293f{
  margin-right: 70px;
}
.backForwardButtons__63abb {
display: none;
}
.toolbar__49508 {
  padding-right: 200px;
}
.visual-refresh .form_f75fb0 {
  display: flex;
  flex-direction: column;
}
.visual-refresh .channelTextArea_f75fb0 {
  margin-bottom: 8px;
}
.visual-refresh .base_b88801 {
  position: static;
  order: -1;
}
/* ───────────────────────── Collapsible SIDE BARS ───────────────────────── */
:root{
  --chat-translate: 491px;
  --panel-expanded: 356px;        /* full panel visual width */
  --sidebar-expanded: 300px;
  --transition-fast: 200ms cubic-bezier(0.165,0.84,0.44,1);
}
/* ───────────────────────── Left Siderbar (Server list) ───────────────────────── */
.sidebarList__5e434 {
  position: fixed;
  bottom: 0;
  left: 0;
  height: 100%;
  pointer-events: none;
  width: 150px; /* collapsed width */
  transform: translateX(-70px); /* tucked left */
  opacity: 0;

  z-index: 998;
  filter : drop-shadow(10px 0px 20px rgba(0, 0, 0, 0.5));
  overflow: hidden;
  contain: style paint;

  transition:
    transform var(--transition-fast),
    width 0.3s cubic-bezier(0.34,1.56,0.64,1), /* bounce only here */
    opacity var(--transition-fast) 0.05s;

  will-change: width, transform, opacity;
}


/* ACTIVE STATE */
.sidebarList__5e434:hover,
.guilds__5e434:hover ~ .sidebarList__5e434,
.sidebarList__5e434:has(~ .sidebarResizeHandle__5e434:hover),
.sidebarList__5e434:has(~ .panels__5e434:hover) {
  transform: translateX(70px);
  width: 300px;
  opacity: 1;
  pointer-events: auto;
}

/* layering */
.guilds__5e434 {
  z-index: 999;
}

/* ───────────────────────── Bottom‑Left USER PANEL ───────────────────────── */
.panels__5e434 {
  position: fixed;
  bottom: 12px;
  left: 6px;
  width: 60px;
  height: 60px;
  border-radius: 30px;
  z-index: 999;
  overflow: hidden;       /* clip inner content if necessary */
  transition: width 0.35s cubic-bezier(0.34, 1.56, 0.64, 1),
              border-radius var(--transition-fast);
  will-change: width;
}
.panels__5e434:hover {
  width: var(--panel-expanded); /* 356px */
  height: auto;                 /* dynamic height for content */
 box-shadow: 5px 0 10px rgba(0,0,0,.75);

 }
.avatar__37e49 {
  position: fixed;
  bottom: 26px;
  left: 20px;
  transform: scale(1.3);
}
/* Inner panel content — in-flow, opacity-only reveal */
.panel__5dec7 {
  position: relative;                    /* keep it in the document flow */
  display: block;                        /* ensure it's a block-level box */
  width: 100%;                           /* fill outer panel's width (outer controls final width) */
  box-sizing: border-box;
  opacity: 0;                            /* start hidden */
  pointer-events: none;                  /* avoid interaction when hidden */
}
/* Hover: reveal instantly with the same ease curve */
.panels__5e434:hover .panel__5dec7 {
  opacity: 1;
  pointer-events: auto;
}
.plated__37e49 {
  padding-left: 50px;
}
.layer__59d0d:has(.tooltip__4e35b) {
  left: 370px !important;
}

/* ───────────────────────── Hide RESIZE handle ───────────────────────── */
.sidebarResizeHandle__5e434 {
  display: none;
}
/* ───────────────────────── Members list (right sidebar) ───────────────────────── */
.membersWrap_c8ffbb {
  position: fixed;
  top: 56px;
  right: 0;                         /* anchor at right */
  height: 100%;
  width: 255px;                     /* final visible width (adjust if needed) */
  transform: translateX(255px);      /* start hidden offscreen to the right */
  opacity: 0;
  z-index: 999;
  filter: drop-shadow(-10px 0 20px rgba(0,0,0,0.6)); /* subtle right-side shadow */
  transition: transform var(--transition-fast), opacity var(--transition-fast);
  will-change: transform, opacity;
  contain: style paint;
}
/* reveal on hover (hovering the members wrapper itself) */
.membersWrap_c8ffbb:hover {
  transform: translateX(0); /* slide into place */
  opacity: 1;               /* fade in */
}
/* ───────────────────────── Fade bottom of channel list ───────────────────────── */
.wrapper_ef3116 {
  -webkit-mask-image: linear-gradient(to bottom, black 90%, transparent 100%);
  -webkit-mask-repeat: no-repeat;
  -webkit-mask-size: cover;
}
.typing_b88801 {
  height: 0px;
}
/* ───────────────────────── User profile ─────────────────────────  */
.user-profile-sidebar {
  position: fixed;
  bottom: 0;
  right: 0;                         /* anchor at right */
  height: 945px;
  width: 340px;                     /* final visible width (adjust if needed) */
  transform: translateX(339px);      /* start hidden offscreen to the right */
  opacity: 0;
  z-index: 999;
  filter: drop-shadow(-10px 0 15px rgba(0,0,0,0.5)); /* subtle right-side shadow */
  transition: transform var(--transition-fast), opacity var(--transition-fast);
  will-change: transform, opacity;
  contain: style paint;
}
/* reveal on hover (hovering the members wrapper itself) */
.user-profile-sidebar:hover {
  transform: translateX(0); /* slide into place */
  opacity: 1;               /* fade in */
}
/* ───────────────────────── Voice text chat ─────────────────────────  */
.chatLayerWrapper__01ae2 {
  position: fixed;
  top: auto;
  bottom: 0;
  right: 0;                         /* anchor at right */
  height: 975px;
  width: fit-content; /* <— key part: automatically fit to child’s width */
  transform: translateX(calc(100% - 1px)); /* move by its own width minus 1px */
  opacity: 0;
  z-index: 999;
  filter: drop-shadow(-8px 0 18px rgba(0,0,0,0.22)); /* subtle right-side shadow */
  transition: transform var(--transition-fast), opacity var(--transition-fast);
  will-change: transform, opacity;
  contain: style paint;
}
/* reveal on hover (hovering the members wrapper itself) */
.chatLayerWrapper__01ae2:hover,
.chatLayerWrapper__01ae2:active {
  transform: translateX(0); /* slide into place */
  opacity: 1;               /* fade in */
}
.channelChatWrapper_cb9592 {
  position: fixed;
  bottom: 0;
  right: 0;                         /* anchor at right */
  height: 975px;
  width: fit-content; /* <— key part: automatically fit to child’s width */
  transform: translateX(calc(100% - 1px)); /* move by its own width minus 1px */
  opacity: 0;
  z-index: 999;
  filter: drop-shadow(-8px 0 18px rgba(0,0,0,0.22)); /* subtle right-side shadow */
  transition: transform var(--transition-fast), opacity var(--transition-fast);
  will-change: transform, opacity;
  contain: style paint;
}
/* reveal on hover (hovering the members wrapper itself) */
.channelChatWrapper_cb9592:hover,
.channelChatWrapper_cb9592:active {
  transform: translateX(0); /* slide into place */
  opacity: 1;               /* fade in */
}
.page__5e434 > div > div:nth-child(2)
{
  min-width: 0px!important;
}
/* OTHER */
.voice-user-button-container {
  padding-right: 0px;
  margin-left: -10px;
}
.voice-user-buttons{
  padding-left: 10px;
}
.list_c3cd7d {
  padding-left: 8px;
}
