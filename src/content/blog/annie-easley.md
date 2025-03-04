---
title: "Rocket Woman: Soaring with Annie Easley's Cosmic Calculations 🚀"
pubDate: 04/03/2025
author: "James Best"
tags:
  - "Brilliant Boffins"
  - "Space Explorers"
  - "Maths Magic"
description: "Get ready to blast off into the amazing story of Annie Easley, a trailblazing mathematician and 'human computer' who helped NASA explore the cosmos! You'll learn how her numerical wizardry launched rockets, discover mind-blowing moon facts, and put your coding skills to the test with a lunar lander challenge."
imgUrl: "../../assets/annie-easley.png"
layout: "../../layouts/BlogPost.astro"
---

# Rocket Woman: Soaring with Annie Easley's Cosmic Calculations

## Let's Discover Something Amazing

Have you ever dreamed of travelling to the Moon? 🌙 Well, meet Annie Easley – the "rocket scientist" whose clever calculations helped make that dream a reality for astronauts!

Back in the 1950s, when digital computers were just emerging, teams of human "computers" like Annie did all the complex maths for NASA's ambitious space missions. Her numerical wizardry was vital for getting rockets off the ground and spacecraft safely into orbit.

![Annie Easley](../../assets/annie-easley.png)

Pretty amazing, right? Let's explore how this mathematical mastermind left her mark on space exploration!

## Time to Get Our Hands Dirty

You know those cool video games where you pilot a lunar lander? Well, get ready to try it for real... sort of! We're going to code up our own text-based lunar lander game.

> 📌 **Adult supervision required for this activity. Make sure to have a parent or teacher nearby!**

### Materials Needed

- A computer, laptop or tablet
- Access to an online Python editor like [repl.it](https://repl.it/)

### Coding Challenge

1. Open a new repl in Python3 on repl.it
2. Let's first set up our lunar lander's starting fuel level and altitude:

```python
fuel = 1000
altitude = 1000
```

3. Now we need to write a loop that will run until the lander either runs out of fuel or reaches the surface. Add this code:

```python
while fuel > 0 and altitude > 0:
    # Your landing logic will go here!
```

4. Inside the loop, we'll get the burn rate from the user. Add this line:

```python
    burn = int(input("Enter burn rate (0-200): "))
```

5. We need to adjust the fuel and altitude based on the burn:

```python
    fuel -= burn
    if burn > 200:
        print("Burn rate too high! Crash landing.")
        break
    elif burn <= 0:
        altitude -= 20
    else:
        altitude -= burn/10
```

6. After the loop, let's print out the landing status:

```python
if altitude <= 0:
    print("Landed safely!")
else:
    print("Ran out of fuel. Crash landing!")
```

7. Run your code and try to land smoothly by managing your burn rate!

> 💡 For an extra challenge, you could add randomness to simulate air turbulence or track your distance from the landing site.

By breaking it down into small steps, you've coded up a fun little lunar lander simulator! Annie Easley and her team had to do enormously complex calculations, but their work allowed dozens of spacecraft to touch down successfully on other worlds.

## Mind-Blowing Facts

- The Moon's gravity is one-sixth as strong as Earth's, which is why astronauts could bounce around so easily!
- We've left over 96 bags of trash on the lunar surface from various Moon missions. Litterers of the cosmos! 😆
- The Moon's spin has slowed down over billions of years due to Earth's gravitational pull, so it now rotates and orbits at the same rate. That's why we only see one side of the Moon from Earth.
- At its closest, the Moon is just 225,623 miles (363,104 km) from Earth. That's less than the circumference of our planet!

## Your Turn to Explore

Annie Easley was born in 1933 and faced many obstacles in pursuing her passion for maths and science as an African-American woman. Through determination, she became one of the first minority graduates of her university and worked her way up to become a leading computer scientist and mathematician at NASA.

Here are some extra missions for you daring space explorers:

- Research other "Hidden Figures" like Dorothy Vaughan and Mary Jackson who overcame discrimination to achieve amazing things.
- Try coding up a gravity simulator to visualize how different planetary masses affect orbits.
- Calculate your weight on the Moon by dividing your Earth weight by 6!
- Design your own lunar rover or Moon base, considering the unique challenges of the environment.

The sky is nowhere near the limit when it comes to STEM exploration. Just look at inspirational pioneers like Annie Easley!

## The Big Question

Isn't it incredible that a brilliant mind like Annie Easley's played such a vital role in one of humanity's greatest achievements – landing on the Moon? Her story shows how mathematics and coding are the launch pads for so many amazing real-world adventures.

So, what unexplored frontier will your curiosity and passion for STEM open up next? The cosmos awaits your cosmic calculations! 🌍🚀

