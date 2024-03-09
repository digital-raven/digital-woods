# A Raven's Guide through the Digital Woods

The woods are only scary until you learn to find food. Then it becomes home.

## Forward
I'm writing this book because I've learned how to extract tremendous
long-term value by demanding the highest standard of treatment from
service providers, product manufacturers, and software developers.

You're an honest person who deserves optimal solutions to your problems.
These are solutions that deliver the most time-savings for the best price.

This book is designed to deliver strategic and permanent value from
an experienced perspective. The sooner you implement these practices,
the more of your life you will get to enjoy doing business with those
you respect.

These lessons should be understandable by anyone using the internet.
If you find yourself reguarly...
- Struggling to remember passwords and worry about being hacked.
- Are uneasy about living life in a way you don't control.
- Want permanent technical competance and agility.
- Just want a computer that does the dang thing and shuts up.

Then this book is for you.

## Think like a Raven
Ravens have pretty good lives for birds. They find food enough in their
woods for them and their kin, and they're clever and fun enough to play
tricks on other animals and fly upside down.

They work cooperatively with otherwise vicious animals. What wolf doesn't
value a scout, and what raven would pass up the muscle?

In literature they represent resolve and a standard of excellence. They
instill fear in those caught under their shadow, but oppresion was only
ever in the eye of the beholder.

And they can soar.

### A Raven's Spellbook
I decided to write this book when I thought of all the ways my computer skills
helped those around me in meaningful ways. These were instances where regular
people were astounded by what I believed were simple tricks.

- `rclone` lets me access a library of media I own anywhere in the world.
- `yt-dlp` can rip videos from youtube and save as any format.
- `ffmpeg` can effortlessly convert videos from one format to another.
- `photorec` allowed me to recover precious memories I've accidentally deleted.
- Simple command line tools like `rename` make organizing and bulk-renaming easy.
- `docker` lets me have a personal development environment that I can bootstrap on
  any machine in the world starting from nothing other than an email account.
- Emulators let me and my friends play classic video games over the internet. These
  games
- `syncthing` lets me move music into a folder that instantly shows up on my phone.
- `discord` allows my friends and I to effortlessly socialize while we play any game.

And the way I use my computer lets me instantly get these programs for free, instantly,
and with no account, in a moral and legally clean way. Each of these is created by
communities of real people, and if they ever break our trust then we can choose to
simply not accept their new versions while we seek a replacement.

No tool or servant of a raven is above replacement.

## Understanding computers and the internet
Computers come in all shapes and sizes, but they all boil down to filing
cabinets that talk to each other. Each computer is just a filing cabinet
with folders in it, and little bots run around and organize the folders.

The internet is just the infrastructure to allow these filing cabinets to
talk to each other. There is nothing **special** about the internet to
anyone. The internet *itself* treats all equally. That isn't true for
everyone but we will make it true for ourselves.

There are some files we should manage, but sometimes we should trust others.
If the problem is better solved long-term by doing it ourself, then we will
**do it ourselves and to solve it once**. Our time is all we have.

If we must pass on the work to someone else then they must **prove themselves
to others before we approach them**. When we do we will be ultimately
trusting and friendly; as we are to any servent. We will also make clear to
ourselves what their strategic function is and isolate their responsibility.
If they screw around then we can easily fire them. The labor market is heavily
competitive, so a raven **never tolerates misbehavior from his servents**.

A raven maintains this mindset in order to create an uncompromising kit.
You're skilled enough to assemble such a kit so let's begin.

## Strong email and passwords
A raven's email **is** his identity, so the first thing we need to cover is
how to present yourself.

It may be tempting to use one password and email for everything. I used
to do that until my Facebook was hacked and I was embarrased in front of
all my friends. I also had to manually change my password across near
100 accounts because I used similar credentials almost everywhere. In
a worse world that could have been my bank account.

If we just use one email address and one password everywhere to save initial
brainpower then we may find ourselves on the news in a data breach. The
initial inconvenience of organizing credentials is *much* more worthwhile
than calling a legal firm over identity theft. This means Target could
compromise our *whole life* if we presented ourselves in this way.

The solution is to give a unique email and password to each and every person
we do business with, but memorizing these is hard. If we try that then we'll
screw ourselves. Since computers are the worlds greatest filing cabinets we can
use them to create an organization that handles that for us.

Fortunately we can solve this problem using only one email provider and a
password manager. The next sections will cover how.

### Selecting an email provider
Our goal is to create an organization where all of our login credentials
are recoverable in one private place. A raven needs an email provider who
is...
- Secure. They must advertise encrypted email that not even they can read.
- Reliable. They need to be up and ready to serve us when we're on the fly.
- Secret. They must allow us to remain anonymous until we break the seal.
  We tell who we are; our servants don't.
- Easy to organize. It must have a great user-interface and intuitive way
  to filter emails.
- 2FA must be optional because **one of our accounts must not have 2FA**.

### Your Core Email
Once we've vetted email providers then we will create 2 accounts with one
of them. We ned a **core email** and an **emergency email** account.

Neither of these accounts will be given out directly to service providers.
We will create an account on a separate service that allows us to generate
aliases that send all email to our **core account**; one for each provider.
This lets us keep all our email in one place while never compromising the
real address.

This has several benefits. All email we receive will show up as sent from
addresses we created. This makes it easy to sort our email into intuitive
folders without regard for the odd naming conventions of each and every
service provider's emails systems.

### Emergency email
Your emergency email is the email account of last resort. In the event you
lose all your devices, this is the email you use to bootstrap yourself
back in to your personal digital ecosystem.

For this reason, this email must be kept top secret, and you must never
forget its password.

When you create this email you will send one email to itself. This email
contains the recovery keys for your core email.

### Unconventional password security
Password security is easy.
- Memorize as few passwords as possible.
- Never change a password have to remember, but give it the works; letters,
  numbers, symbols, long, and memorable. These are a pain to remember, so lets
  only have like 2 or 3 of these.
- Every other password will be randomly generated and managed by our one and
  only **password manager**.

**These rules do not pertain to organization accounts**. Organizations
should help their members execute on these rules, but many don't and they're
immune to reason. If that's the case in your company then you should perform
the minimum requried by your IT company.

There are many myths floating around about password security. I'll dispel a few.
- Changing your password does not make it more secure. An expert pen-tester
  named PirateSoftware would pwn accounts at Blizzard Entertainment because
  employees would just increment a number when forced to change. Just one example.
- If you receive notice that a service provider has been compromised, then you
  change your password.

### Email and password example
There are many competant providers of email, but a Raven only needs one. Let's
choose the best one.

The email I trust the most is ProtonMail. You can make an account there without
telling them your name or setting up 2FA. This makes them the easiest to set up.

The strongest indicator of trust is their brand, which uses simple language to
communicate their respect to you. They have faced the necessary scrutiny from the
cybersecurity community and all their client-side tools are free and open source.
These are the marks of a trustworthy company.

So I use ProtonMail for my **core and emergency emails**. They've treated me well.

ProtonMail also runs simplelogin.io, which provides unlimited email aliasing
for $30 a year. This is a fantastic deal!

So create your **core email**, set it up with **Aegis** smartphone authenticator
for 2FA, and then copy the **recovery codes** and save them by emailing them
to yourself to/from your **emergency account**. Each of these codes is a one-time
use to login back to your **core email**.

**Make sure you protect your core email with 2FA**. Use a smartphone authenticator.
I recommend Aegis because it's free and open source. Download that to your smartphone
and use that.

### Story time!
Rabbi is a great friend of mine and she likes shopping. She followed all the steps
and can enjoy quick and easy logins to all her shopping websites and bank and only
needs to remember 3 passwords.

But one day her phone was stolen while it was logged in to her **core email** account.
This is a problem that requires immediate action. Rabbi decided to go to a local shop
and explained the problem.

The shop keeper let her use their computer to **log in to her emergency email**, and
then she **burns a recovery code** to **login to her core email** and **commands ProtonMail
to log her out everywhere**. Her digital life is now secure. Thank goodness! Now she can
buy a new phone, and doesn't even have to worry about changing any passwords!

She *could* migrate her remaining recovery keys to a new emergency email and delete
the old accocunt to be really safe, but she'll probably be fine enough.

## Personal computer
There are 2 main reasons why I use a computer. Phones have their own section.

- Graphics computers, which are still best served as physical machines you own.
  Graphics cards are more expensive no matter who runs them.
- her computer is just for web-browsing or working.

Well if any other computer is *just* for working... I bet we can create a
mobile computing environment that lets us bring our

## Health care
Imagine if all the woodland creatures paid a small portion of their food to a
structure that could alleviate any long term health care concern to those whose
die-rolls came up short.

Such a structure does not exist in the United States, but there is a way to maximize
health care value. If you shoot yourself in the head with a gun that won't kill you
then your city will pay your insurance deductible. This means you get 1 year of health
care for free. This will also risk your imprisonment in an asylum.

I do not recommend this.
