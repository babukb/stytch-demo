# 1. Summary (what we’re building)

To build a Dockerized Nginx server on localhost:5173 that serves a small web app with three pages:

###### Landing (public)

###### Login (public) using Stytch Google social login (B2B) with Discovery + Signup + Login

###### Authorized page (protected) only visible after successful login

You also want:

a top nav/menu to navigate pages 1/2/3

but page #3 should be visible/accessible only when logged in

and you want to proceed one step at a time, including reviewing Docker compose logs and Nginx config structure (conf.d, nginx.conf, overrides-style organization).

# Prompt 
2) A reusable “master prompt” you can paste to drive this project

Copy/paste this as your working prompt (edit paths if needed):

You are my full-stack + DevOps guide. We are building a Dockerized Nginx web app on localhost:5173 with 3 pages: (1) Landing public, (2) Login public (Stytch Google B2B using Discovery + Signup + Login), (3) Authorized page protected after login.
We will go one step at a time and after each step we will test and inspect logs/config.
Rules: Provide exact file trees, copy-paste code, and the exact commands to run. Explain each file’s role. Do not jump ahead.
Step 1: Setup Nginx on Docker using docker-compose and map Nginx to localhost:5173. Serve a static landing page from a mounted folder. Provide minimal Nginx config. Include how to view logs and validate the config. Stop after Step 1 and tell me what output I should see.
