<!--
  PHASE 2 -- Self-hosted stats cards.
  This one needs a few manual steps first (token + a free Vercel deploy) since
  the public github-readme-stats instance is shared by everyone and constantly
  rate-limited. Steps:

  1. github.com/settings/tokens -> Tokens (classic) -> Generate new token (classic)
     Note: readme-stats, Expiration: No expiration, Scope: tick "repo"
     Generate, then COPY IT IMMEDIATELY (GitHub shows it once).
     Never paste this token into a chat, a public repo, or a website --
     it only ever goes into Vercel's environment-variable field below.

  2. Fork https://github.com/anuraghazra/github-readme-stats

  3. https://vercel.com -> Sign up with GitHub -> Hobby (free) plan
     -> Add New... -> Project -> Import your fork -> leave build settings alone

  4. Under Environment Variables: name = PAT_1, value = the token from step 1
     -> Deploy, wait ~2 min

  5. Copy your instance URL (looks like your-project.vercel.app), then replace
     every "YOUR-INSTANCE" below with it.

  Verify it worked: open
  https://YOUR-INSTANCE.vercel.app/api?username=sreeram-in&show_icons=true
  -- a themed card should render (not a rate-limit error).
-->

<div align="center">

<img width="100%" src="https://streak-stats.demolab.com/?user=sreeram-in&hide_border=true&background=0A101F&stroke=22D3EE&ring=A78BFA&fire=10B981&currStreakLabel=22D3EE&sideLabels=94A3B8&currStreakNum=F8FAFC&sideNums=F8FAFC&dates=64748B&titleColor=22D3EE&card_width=1180" alt="streak" />

<br/>
</div>

<!--
  hide_rank=true is intentional: the letter grade is weighted heavily toward
  stars/followers, so a newer account sits at "C" regardless of how much you
  code. Hiding it is the more honest read on a fresh profile like yours.
-->
