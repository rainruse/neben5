# neben5

[CAUTION: WORK IN PROGRESS. Beware of aspirational ramblings ahead...]

This experimental project explores a parallel path to [L5](https://l5lua.org/),
asking, "What if L5 was built on SDL3 + Lua 5.4 instead of LÖVE?".

This is not a fork of L5. It's not affiliated with, sponsored by, or approved
by L5 or the Processing Foundation. I'm not trying to compete with L5. This is
just a proof of concept resulting from me getting curious, thinking, "Hey, L5's
core idea of Lua + Processing + Permacomputing is cool, and I wonder if there's
a way to implement that with fewer sharp edges."

Also, I got nerd-sniped by the LÖVE duck balloon, which is very weird and
confusing. I'm wondering, could L5 be built differently, so that nobody ever
gets ambushed by the duck balloon?

Key Research Questions:
- Can I make an interactive HTML5 playground thing for inline use in API docs?
- Can I make a tolerable HTML5 based edit and run workflow that stays true to
  the L5/Permacomputing principle of Expose the Seams?
- Can I make a low-friction install (no-install?) workflow to make it easy for
  first-timers to try creative coding examples in Lua on macOS, Windows, or
  Linux?


## Working Within Limits

I aim to do this work with respect for the guiding principles of L5, but at the
same time, allowing myself a bit of wiggle room to explore paths not taken.

Hard Constraints:
- 100% human authorship (see L5 AI Usage Policy)
- Design for viability on old and low-spec hardware
- Design for community health and inclusiveness
- Design for resilience

References:
- Tusman, L., & Kuksenok, K. (2026). Designing L5: A Permacomputing Approach to
  Creative Coding. In LIMITS '26: Workshop on Computing within Limits.
  [arXiv:2606.18481](https://arxiv.org/abs/2606.18481)
- AI Usage Policy stated in L5's
  [CONTRIBUTING.md](https://github.com/L5lua/L5/blob/main/docs/CONTRIBUTING.md#ai-usage-policy)
- L5 usability report:
  [beginners](https://ashgreyseafoam.com/L5_usability_studies_beginners.pdf)
- L5 usability report:
  [experienced](https://ashgreyseafoam.com/L5_usability_studies_experienced.pdf)


## Copyright & License

The vendored third party code in [./vendor](vendor) includes its own copyright
and license notices. TLDR: Lua is MIT, SDL3 is Zlib.
