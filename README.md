# Precourse 02 Assessment

## Guidelines

- Assessments are meant to give you an idea of how well you understand--or can figure out--the material that you covered recently.
- Do at least a little work on *every* prompt. Even if you don't have time to write code, leave comments that describe your intent at as granular a level as you have time for. Leaving a prompt blank is tantamount to failing a prompt and you'll get much more credit for attempting it at all, even if only in the form of comments about your intent or pseudo-code describing your plan. It's important you've done at least a little work on all the prompts, before returning to complete the ones that sees easiest to you.
- You **must** submit a pull request for all assessments (guidelines below). Give yourself a few minutes to do this at the end of the time allotted for the assessment.
- The help button is available to you during assessments, how often you use that service is up to your own discretion.
- What you see is what you get--most of the time we don't include outside libraries.
- TIP: Don't take too much time writing tests that are not required, instead use your Chrome Console for a quick and easy way to test your code.


## Grading Outline

- [ ] underbar-map
- [ ] underbar-uniq
- [ ] underbar-memoize
- [ ] underbar-extend

## Using and Referencing Outside Resources

While ignoring complexity and conjuring are great skills for you to develop as a software engineer, assessments are not the time for you to conjure. Assessments are intended to expose not only your ability to implement certain solutions, but *also* your understanding of the solutions you implement.

In assessments, we develop challenges that represent the kinds of challenges you'll face in the real world. One primary characteristic of the work you'll do in industry is that you won't be able to find an existing solution to the exact problem out on the internet. *Thus, in any assessment, you should not be referencing code that solves the specifics of the problem you're being asked to solve. You can reference things that help you to understand the problem at hand, but not if they subvert the intent for the prompt to be an assessment of what you personally understand.*

Academic dishonesty is any time you purposefully make it difficult to correctly determine how well you understand the material you're being tested on, by representing as yours work that you didn't do. As such, you should endeavor to either solve all these problems yourself, limit yourself to resources that are representative of what you would have when solving a truly novel problem, or make sure to site the source of your reference in a comment if you believe there is *any* chance it could be construed as a potentially unfair advantage to have access to. When in doubt, cite the source and explain any concern you might have.

## Self-Grading Process

After you complete each prompt, assign a grade to each item in the above Grading Outline, using this [Grading Scale](https://github.com/remotebeta/student-wiki/wiki/Self-Assessments). Note your grade by editing **this file** (`README.md`), and writing your grade next to the corresponding item in the Grading Outline above. Please use the exact terms shown in the [Grading Scale](https://github.com/remotebeta/student-wiki/wiki/Self-Assessments) document; do not modify or improvise them.


## Javascript Syntax Check

The file `syntaxalyze.html` is included. Open it in your browser and then drag your solution files onto the page to perform a syntax check. Fix any errors listed, then repeat the check. To re-check your file, you must **drag the solution file into syntaxalyze after each edit** &mdash; refreshing the page will not work. You may need to perform these steps multiple times until all the errors are fixed.

## Submitting Solutions

**VERY IMPORTANT: Before submitting your solutions, find and fix all syntax errors**

Solutions are submitted via [Pull Request](https://help.github.com/articles/using-pull-requests). Follow these steps:

1. From **your fork**, select `Pull Requests` and then create a `New pull request`. 
2. STOP. *Before* you `Click to create a pull request for this comparison` you must **adjust the target branch** (aka `base branch`) to be your username. Once changed, the pull-request heading should look like this:

  > remotebeta:username ... username:master

3. Copy and **paste the completed Grading Outline into the comment block** of your Pull Request.
4. Click `Send pull request`

---


## map
Return the results of applying an iterator to each element in a collection.

* [ ] Implement a `_.map` function



## unique
Return a duplicate-free version of the collection.

* [ ] Implement `_.uniq` function

## memoize
Return a function that, when called, will check if it has
already computed the result for the given argument and return the precomputed  value instead when possible.

* [ ] Implement an `_.memoize` function

## extend
Extend a given object with all the properties of the passed in object(s).

* [ ] Implement an `.extend` function
