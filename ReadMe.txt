07 Nov 2024
===========

ref: Build a Real-Time Chat App with NextJS, React, ShadcnUI, and Tailwind
	Code Complete
	https://www.youtube.com/watch?v=WmMHbLzQI98

-------------------------------------------------------------
Tech Stack
React, NextJS

Tailwind CSS, Shadcn Components, Convex Database, Clerk for Authentication

There's a Udemy course which has additional features - audio/video/Mobile App
-------------------------------------------------------------
-------------------------------------------------------------
VS Code
	I'm on a Windows 10 Laptop with WSL Ubuntu 22.04
	From within WSL, launch VS Code by typing 'code .' from the root directory of project
-------------------------------------------------------------
node -v
v20.17.0

npx create-next-app@latest
-------------------------------------------------------------
root@DESKTOP-V99LATL:~/dev/ChatApp/ChatApp# npx create-next-app@latest
Need to install the following packages:
create-next-app@15.0.3
Ok to proceed? (y) y

✔ What is your project named? … chat-app
✔ Would you like to use TypeScript? … No / Yes
✔ Would you like to use ESLint? … No / Yes
✔ Would you like to use Tailwind CSS? … No / Yes
✔ Would you like your code inside a `src/` directory? … No / Yes
✔ Would you like to use App Router? (recommended) … No / Yes
✔ Would you like to use Turbopack for next dev? … No / Yes
✔ Would you like to customize the import alias (@/* by default)? … No / Yes
Creating a new Next.js app in /root/dev/ChatApp/ChatApp/chat-app.
-------------------------------------------------------------
root@DESKTOP-V99LATL:~/dev/ChatApp/ChatApp# ls
ReadMe.txt  chat-app
-------------------------------------------------------------
cd chat-app/
npm run dev
-------------------------------------------------------------
Setting up Shadcn - The Component Library
Google Chrome
	https://ui.shadcn.com/
	https://ui.shadcn.com/docs/installation/next

Terminal
	npx shadcn-ui@latest init
	[??] As of 07 Nov, this command is not listed in the shadcn page, and is not working on the terminal as well

	And quite right, they have a message on the page
		If you're using Next.js 15, see the Next.js 15 + React 19 guide.
		https://ui.shadcn.com/docs/react-19
	However, React 19 is still RC, and I have 18.3.1 which is the latest as of today, and I could not install 19 anyways
	So lets stay with 18.3.1
	
	[Fix]: ref: https://stackoverflow.com/questions/78934468/shadcn-ui-commands-on-terminal-is-not-working
	shadcn-ui library has been renamed to shadcn
	install using 'npm install shadcn' (Note: npm install, not npx)
Terminal
	npm install shadcn
		You might see this in output
		2 high severity vulnerabilities

		To address all issues, run:
  		npm audit fix
	npm audit fix --force
	npm install shadcn-ui

		Troubleshhot:
		npx shadcn@latest init resulting in this error
			request to https://ui.shadcn.com/r/styles/index.json failed, reason: unable to get local issuer certificate

		[Fix] ref: https://stackoverflow.com/questions/36494336/npm-install-error-unable-to-get-local-issuer-certificate
		export NODE_TLS_REJECT_UNAUTHORIZED=0
	export NODE_TLS_REJECT_UNAUTHORIZED=0
	npx shadcn@latest init
-------------------------------------------------------------
From the Shadcn webside, copy the command to install Button

Terminal
	npx shadcn@latest add button
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------
-------------------------------------------------------------


