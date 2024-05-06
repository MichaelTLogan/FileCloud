# CSC 4026 Final Project
Michael Logan
5/5/2024
CSC 4026

The purpose of this project is to serve as my own personal video file storage cloud. I intended to add video editing functionality as well but ran out of time after my laptop got stolen.

I'll be honest, I don't feel good about this project because it doesn't match my end vision at all. To me it feels too incomplete but at least the essential functionality is there. I struggled with learning React and AWS Amplify. I am not very good with back-end stuff. If I could go back and restart this project, I would see if I can find a way to do it in a language that I wouldn't have had to learn from scratch.

Even though right now this is an assignment for a class, it is something I genuinely have some passion for. I intend to take what I've learned from this and turn it into a fully functional and intuitive app which serves the same purpose. Some updates to this project were lost because I forgot to push them. Oh well.

My build process is unfortunately quite un-involved. Some deployments have gone very smoothly while others have been torture. My most recent deployment refuses to work. The way I set up my amplify project basically has me push my newest version to main and then amplify pulls the update and deploys it. Because my most recent deployment doesn't work it reverted to before I merged branches and doesn't reflect a few features I've added. 

# Viewing the project
You can access the live deployment at the link I included in the assignment dropbox, although based on what I said before I would skip that and just build the project locally. Here's how you can do that:

First of all, I did my development using the following:
```
Ubuntu 24.04 LTS Virtual Machine
Nodejs version v18.19.1
npm version 9.2.0
```

You will need nodejs, npm, and a couple packages from npm.
```
sudo apt update
sudo apt install nodejs npm
npm install aws-amplify @aws-amplify/ui-react
```

Once you've got these prerequisites you should be ready to go and run the following:
```
npm start
```
