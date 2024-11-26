# 🍿 Popcorn

GPU programming is still too hard, and the current LLMs aren't helping much. ChatGPT and others make a mess of CUDA code because they don't really get how GPUs work. But we've seen projects like llm.c where humans and AI actually work together to write decent systems code.

We think we can build something better by focusing specifically on GPU programming. It's going to take work - we need better training data, smarter ways to test code, and a real understanding of what makes GPU code good or bad.

We're doing this in public because, honestly, it's the only way this kind of project makes sense. All our training runs, our conversations about what works and what doesn't, our infrastructure - it's all going to be open. If you want to help figure this out, join us.

## Where to Find Us
We mostly talk on discord.gg/gpumode in the popcorn channel. It's pretty casual - drop in when you can.

## What We're Working On

### Data
We're collecting every CUDA and Triton kernel we can find. We need more examples of good GPU code than what's currently out there. We're also building proper benchmarks so we can actually tell if what we're doing is working.

### Infrastructure
We need compute - looking to get about 100 GPUs for 6 months. We're building tools to track progress and share results in real-time through Discord. Nothing fancy, just functional.

### Research
We're trying to figure out the fundamentals - what do we need to tell an LLM about GPUs for it to write good code? How many times should we sample to get better results? What feedback actually helps?

### Language Design
We think some abstractions (like Thunderkittens) might make this whole thing easier. If that proves true, we'll push to get more people using and improving these tools.

More coming soon. Join us if this sounds interesting.