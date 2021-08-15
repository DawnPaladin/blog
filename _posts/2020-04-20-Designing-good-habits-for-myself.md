---
layout: post
title: "Designing good habits for myself"
comments: true
---

<a href="https://undeadfaerie2631.tumblr.com/post/615410798181924864/and-theres-the-really-important-4th-day-the-day">From Tumblr:</a>

<img class="meme" src="{{'/assets/2020-04-20/days-of-the-week.png' | absolute_url }}" alt='boxofleftovermuffins: "Due to corona we have 3 days of the week now: yesterday, today, tomorrow". candyradium: "this is just what having adhd is like". undeadfaerie2631: "And there’s the really important 4th day: The day of The Appointment. No one knows how far away it is, but it exists. Looming in the background, waiting to strike."' />

<!-- cut -->

---

<br/>

In the Age of Quarantine, different people have different forms of self-care. Mine is productivity.

Presently I'm job-searching full time. Job searching means feeling uncertain a lot. You can't control the number of nibbles you'll get back a particular week; what you can control is how much work you put into the job search.

But there's a difference between *being* productive and *feeling* productive. I needed something to link the two: when I've done lots of work, I want to feel good about that, and I need something that will tell me whether I have or haven't done enough today.

For a long time I've used <a href="https://habitica.com/static/home">Habitica</a> as a to-do list and habit tracker. This has several big benefits: it lets you define things you want to do (once or regularly) and rewards you for doing them with level-ups, loot, and new abilities. It's even better when you join a party. But as with most gamified systems, eventually it runs out of relevant rewards. As of this writing, my Warrior is level 80 and has achieved every interesting goal Habitica can provide. So I decided to build a system better tuned to my own needs.

<a class="click-to-embiggen" href="{{'/assets/2020-04-20/effort-tracker.png' | absolute_url }}"><img src="{{'/assets/2020-04-20/effort-tracker.png' | absolute_url }}" alt="Effort Tracker, a Google Sheets-based to-do list and more">(Click to embiggen)</a>

There are three time horizons I care about: today, this week, and long-term; these are mapped to the left, center, and right columns.

At the start of each day I decide on my goals for that day and the point value for each goal. 1 point is something simple like brushing my teeth; submitting a job application (which usually includes a custom cover letter and possibly one or more essay questions) is usually 5 points, and a truly herculean task might be 10 points.

Under "Daily Goals" we have "Bonuses". These are things I want to do regularly - not necessarily every day, but I don't want to ignore them for more than a week or so. This includes things like cleaning up around the house, going for a walk, and talking to people besides my wife. Whenever I mark the "✔" column, a script inserts today's date into a hidden column, which the "✔ days ago" column uses to calculate how long it's been since I did that.

Near the bottom we have the "Daily combos" section. This is an important part of the game loop I'm using to train myself to get better at estimating how much I'll be able to accomplish each day. At the end of each day I grade myself on four things:

1. Did I accomplish everything I set out to do that day? If so, Effort Tracker gives me a 25% bonus on all the points I earned that day. The incentive this creates is to not aim too low - a 25% bonus on a small number is unappealing - but also not to aim too high, lest I not complete everything and lose the bonus.
2. Did I achieve all my goals before dinner? It's good for me to be able to rest with my wife in the evening. This is worth another 25% bonus.
3. Did I score three different bonuses today? This is worth a flat 3 points; seeking this bonus often induces me to clean up a little or brush my teeth before bed.
4. Did I score five bonuses today? These don't have to be unique. If I did a truly heroic bout of cleaning or something, I can get a 5-point reward.

Similarly, I have weekly goals and a 20-point bonus for completing them all. At the end of the week we add up the weekly total and put it in the "Weekly totals" column, where it adds to the grand total and the point balance I use to purchase rewards.

Figuring out how to reward myself for the work I'm doing is something I'm still working on. I can spend 150 points on a $5 game microtransaction; I've done that a couple times and run out of things I really want. 

Recently my wife suggested I might be working too hard. The problem is that I feel guilty for resting, and I worry that if I stop pushing myself I will become lazy and never amount to anything. So as a way of establishing boundaries for myself, I've recently ruled that above and beyond weekends, I can spend 500 points to take a day off. I can earn that in two good weeks or three bad ones. I'll continue to monitor this and rebalance it as necessary.

That's my system in its current state. I thought about making this into a web app, but Google Sheets is really easy to change when I decide part of the system needs to be reworked. I've pinned the sheet to my phone's home screen so I don't even need my computer turned on to update it. If anyone wants to use it I can probably make you a template.

I really agree with <a href="https://www.pentadact.com/2019-01-22-my-week/">something Tom Francis said</a> about how he organizes his work time as an indie game developer:

<blockquote class="short-quote">
	<p>Obviously I’m amazingly lucky to have this kind of freedom over my working life. That much freedom can be dangerous: if you don’t consciously get on top of it, create systems and measure the results, you can end up throwing away a huge gift and being miserable despite it.</p>
</blockquote>

The traditional approach to improving your productivity is to make a New Year's resolution, promise yourself really hard that you're going to do better, spend lots of willpower forcing it, and then feel disappointed in yourself when the willpower runs out. I'm not a fan of that approach. I've played enough games in my life that I understand a little about how systems incentivize behavior. [Farnam Street has an excellent introduction to the topic](https://fs.blog/2017/10/bias-incentives-reinforcement/) that opens with this great quote:

<blockquote class="short-quote">
	<p>Never, ever, think about something else when you should be thinking about the power of incentives.</p>
	<footer>Charlie Munger</footer>
</blockquote>

Readers, I'd like to know how quarantine is treating you. Here's a poll, and feel free to add more detail in the comments.

<iframe src="//www.strawpoll.me/embed_1/19828230" style="width:680px;height:426px;border:0;">Loading poll...</iframe>

## Quotes

<blockquote class="short-quote">
	<p>What the pupil must learn, if he learns anything at all, is that the world will do most of the work for you, provided you cooperate with it by identifying how it really works and aligning with those realities. If we do not let the world teach us, it teaches us a lesson.</p>
	<footer>Joseph Tussman</footer>
</blockquote>

## Mocking the Plague

<iframe class="meme" width="560" height="315" src="//www.youtube-nocookie.com/embed/iVC01GxFwDg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<img class="meme" src="{{ '/assets/2020-04-20/cartoon-bears.jpg' | absolute_url }}" alt="Shelter-in-place coping levels measured in cartoon bears. Level 1: Berenstein. Fully clothed, family unit all together, societal rules and standards still being followed, practiced, and respected. Level 2: Pooh. T-shirt and no pants, mostly alone, eating entirely too many sweets, but happy in your blissful ignorance. Level 3: Yogi. Naked except for a hat and tie, surviving off whatever food you can steal, only companion is smaller nude person in a bow tie. Level 4: Charmin. Completely nude, surrounded by others who are completely nude, obsessed with toilet paper." />

<img class="meme" src="{{ '/assets/2020-04-20/batman.png' | absolute_url }}" alt="Scene: Gotham Hospital. Batman, handing box of Bat Masks to surgeon: 'I figure you heroes could use these more than me. They block all viruses, Joker's laugh gas, and microscopic scorpion bees!' Surgeon: 'Uhh, thanks! I dont think we'll need to block all of that, though!' Batman: 'Hahah, well... 2020 isn't over yet.'" />

<img class="meme" src="{{ '/assets/2020-04-20/cats-do-care.jpg' | absolute_url }}" alt="hijabby on tumblr: I'm screaming??? So my cat knows I get upset when he steps on my paintings (not yelling or anything I think he just sees me spend hours trying to cover up what his paws do) in my 'studio' which is a crammed small storage closet with painting all over the floor drying , so like I'm in there rn and I saw him try to get to point A to point b but it was impossible for him to jump over so like he realized the matte parts were dry and like he was stepping on the corners of the painting and every step he'd look at his paw to see if he f***ed up and honestly it was the most thoughtful thing ever I don't ever wanna hear anyone ever say that cats don't care" />

<img class="meme" src="{{ '/assets/2020-04-20/horse-actors.jpg' | absolute_url }}" alt="scrantonpaper on tumblr: 'me, watching a battle scene: please not the horses. leave them alone. they did nothing wrong. they are the only innocent ones. they don't deserve this.' fiyhi: 'honestly this used to upset me a lot as a kit until my mom, who's worked with horses for many years, told me about how they train the horses in those movies to do things like falling down, kneeling, crawling, or stay laying on the ground after they fall. and how it's so tough to train a prey animal to do these behaviors and how hard both trainer and horse have to work. so now whenever i see a horse take a hit and go down in a movie, i just think 'f***ing superb you funky little horse actor'" />

<img class="meme" src="{{ '/assets/2020-04-20/last-supper.jpg' | absolute_url }}" alt="An image of the Last Supper. Jesus is alone at the table; the disciples' faces are visible in small boxes at the top of the image because they're in a Zoom call together." />

## Reading material

- [Red and Blue America Aren’t Experiencing the Same Pandemic](https://www.theatlantic.com/politics/archive/2020/03/how-republicans-and-democrats-think-about-coronavirus/608395/): Political leanings are correlated with where you live, which changes how the pandemic will affect you.

- [Rep. Burchett set up a line for those 'feeling overwhelmed.' So far, he's gotten 1,000 calls.](https://www.knoxnews.com/story/news/2020/04/04/coronavirus-pandemic-tenessee-tim-burchett-mental-health-loneliness-depression/5104937002/): This is good leadership.

## Music

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/eoUsbydHJKA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
