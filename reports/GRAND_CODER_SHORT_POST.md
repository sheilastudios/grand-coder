# Grand Coder and More Diligent AI Engineering

I've spent more than twenty years in systems and infrastructure engineering. Grand Coder grew out of trying to make that experience useful to the AI agents I work with.

I don't primarily think of it as making a model smarter. I think of it as helping a capable model reason and work more diligently.

Our team uses it, and I see clear practical value. We've also run controlled internal evaluations. Those aren't uniformly positive, but there are actual positive results, not just agents telling us they liked the instructions.

One tiered engineering study ran 96 isolated executions. After a documented post-scoring audit excluded two entire task families with invalid hidden requirements, the retained baseline passed 13/18 runs. Three Grand Coder configurations passed 16/18, 16/18, and 15/18. The baseline already had the same matched baseline setup. This measured Grand Coder's additional contribution, not our whole setup against a bare model.

That's a bounded positive result, concentrated in two task families. It isn't a universal 16.7-percentage-point improvement.

Other work found better performance on some stages of an evolving project and a narrow improvement in structured decision accuracy. There were also saturated tests with no difference, apparent wins that disappeared after scoring corrections, and long-duration failures. One build study found better blinded review scores but no corrected behavioral advantage, at higher cost.

I'm keeping the implementation private for now. I'm sharing the findings, including their limits, rather than the instructions or internal design. These are internal historical evaluations, not an independently reproduced public benchmark, and they don't automatically validate every later revision.

The conclusion I stand behind is simple: Grand Coder has produced specific measurable benefits and is useful in our ongoing work. It doesn't need perfect marks for those improvements to matter. It does need honest reporting about where they occurred and where they didn't.

Further testing will wait until after current development priorities ease. For now, this is a field note about work we are already using, not a claim that AI software engineering is solved.
