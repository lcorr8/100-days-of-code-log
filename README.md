<h1 align="center">100 Days Of Code: Personal Challenge</h1>

Hello World! You are about to witness the beginning of an epic 100-day coding journey where I have challenged myself to code outside of work for 100 consecutive days in the hope to solidify new habits that will allow me to continue to learn new and interesting topics outside of work. 

<img src="https://images.unsplash.com/photo-1502101872923-d48509bff386?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2989&q=80" alt="Image of toddler standing in front of beige concrete stairs">

During this time I plan to go back to my Flatiron School curriculum to review everything from the begining and see what I might have missed the first time around. Additionally I'd like to do my final project as I never finished it since I got a job overseas, and moved to Berlin instead.

Without further ado, I present my **100DaysofCode** personal challenge.

<p align="center">
  <img src="https://avatars0.githubusercontent.com/u/16438376?s=460&v=4" alt="Headshot of Laura Correa">
</p>

<p align="center"><b>Follow me on Twitter </b><a href="https://twitter.com/L_corr">here</a>.</p>

<p align="center"><b>Check out my repos </b><a href="https://github.com/lcorr8">here</a>.</p>

<hr>
<br>

<h2 align="center"> Day 1: Tuesday January 8, 2019 </h2>
 
**Today's Progress**: Today I decided to commit to the 100 days of code challenge and I started my visual log inspired by Joe Warren's [How to Transform Your #100DaysOfCode Log Into a Visual Experience](https://medium.freecodecamp.org/how-to-transform-your-100daysofcode-log-into-a-visual-experience-d048334af8d9) article. Additionally I worked on the Intro to Ruby development section of Flatiron School's curriculum through variables(about 16% of the section). Read all of the extra resources, and inspected all of the tests.

**Thoughts** ... wow doing this again I realize I'm taking much more time to read and peruse all resources and book recommendations. I definitely don't think I took enough time to play around before, so i'm enjoying goofing around on the shell and taking this reintroduction less seriously than before. I'm also wondering why on earth I waited so long to dive into the tests the first time around.
<p align="center">
  <img src="https://media.giphy.com/media/5xrkJe3IJKSze/giphy.gif" alt="Testing gif of two car dummies giving a thumbs up.">
</p>

**Link to tweet**
[Day 1](https://twitter.com/L_corr/status/1082777799063158784)

<h2 align="center"> Day 2: Wednesday January 9th into the 10th, 2019 </h2>
 
**Today's Progress**: Today I reviewed Ruby datatypes, array basics, methods and arguments. string interpolation, standard streams (Input/Output).

**Thoughts**: wahh working late into the night is really messing up with my schedule for programming and the log is becoming confusing. Also after a full day of work and evening activities reading/practicing past midnight is not feeling super productive as i'm exhausted. Will attempt to start doing my daily hour in the morning before work next week.

**Link to tweet**
[Day 2](https://twitter.com/L_corr/status/1083488167385358336)

**Link to Articles**
[standard streams wiki](https://en.wikipedia.org/wiki/Standard_streams)

<h2 align="center"> Day 3: Thursday January 10, 2019 </h2>
 
**Today's Progress**: Today I practiced writing Rspec tests, interpolation, default arguments and I refactored some old code in my very first labs.

sample original answer (note the hard coded stuff): 

```Ruby
def display_rainbow(colors)
  puts "R: #{colors[0]}, O: #{colors[1]}, Y: #{colors[2]}, G: #{colors[3]}, B: #{colors[4]}, I: #{colors[5]}, V: #{colors[6]}"
end

# given: ['red', 'orange', 'yellow', 'green', 'blue', 'indigo', 'violet']
# ==> "R: red, O: orange, Y: yellow, G: green, B: blue, I: indigo, V: violet"
```

refactored answer:

```Ruby
#display_rainbow method with an each loop
 
 def display_rainbow(colors)
 	array = []

 	colors.each_with_index do |c, i|
 		array << "#{c[0].upcase}: #{colors[i]}"
 	end

 	puts array.join(", ")
 end

# given: ['red', 'orange', 'yellow', 'green', 'blue', 'indigo', 'violet']
# ==> "R: red, O: orange, Y: yellow, G: green, B: blue, I: indigo, V: violet"
```

**Thoughts** how could I forget how much I love ruby...?!?!?!?!

<p align="center">
  <img src="images/ruby-love.png" alt="Image of Abu from Aladdin holding a ruby."><br>© Disney
</p>

**Tweet**
[Day 3](https://twitter.com/L_corr/status/1083495494960246787)

<h2 align="center"> Days 4-7: January 11-14, 2019 </h2>
 
**Today's Progress**: On Friday and today I switched gears and combined a few days of work in anticipation of some scheduling conflics over the weekend. Additionally I got flexible with the curriculumn and started a course for the AWS Developer certification, on which I will be working on fridays and weekends. This weekend I learned about IAM, EC2, Elastic Load Balancer and Route53. It was super cool to map a domain to the elastic load balancer and then to an EC2 container containing a webserver and seing a 'Hello World!' website.

**Thoughts**: Hoping that my flexible schedule doesn't set me too far back in terms of setting new habits and finishing the Flatiron review I initially set as the goal of this challenge.

**Link to tweet**
[Days 4-7](https://twitter.com/L_corr/status/1084900384492212225)

<h2 align="center"> Day 8: Tuesday January 15, 2019 </h2>
 
**Today's Progress**: Today I read about making CLI applications and I did a review of terminal/bash commands.

**Thoughts**: I know the commands exist but always find myself having to look them up...so i'm adding a [cheat sheet](https://github.com/0nn0/terminal-mac-cheatsheet) in case anybody else wants to review.

**Link to tweet**
[Day 8](https://twitter.com/L_corr/status/1085789710889435136)

**Reference links** 
[29 Linux Commands You Must Know](https://www.hongkiat.com/blog/basic-linux-commands/), [Modify File Permissions with chmod](https://www.linode.com/docs/tools-reference/tools/modify-file-permissions-with-chmod/), [Ownership and Permissions](https://access.redhat.com/documentation/en-US/Red_Hat_Enterprise_Linux/4/html/Step_by_Step_Guide/s1-navigating-ownership.html),
[Permissions
](http://linuxcommand.org/lc3_lts0090.php), [Change permissions for a file in Unix
](https://kb.iu.edu/d/abdb), [How to Set File Permissions Using `chmod'
](https://www.washington.edu/computing/unix/permissions.html).