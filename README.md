# Casus-custom-Chatfill-II
A modified Sillytavern preset.  All credit to u/eteitaxiv for the spectacular original, which you can find at the link below.  I'm sharing mine here mostly on the off chance that he might want to incorporate some of what I've done in his next version.

https://www.reddit.com/r/SillyTavernAI/comments/1tb3d78/chatfill_v2_now_with_revolutionary_switches/

As for what I changed/added:

1. A 'preamble' message at the very top for use with Deepseek v4.  Preamble just says that everything below it supersedes prior instructions.  People seem to think that Deepseek is 'nerfing' v4 by injecting instructions before the model sees your prompt.  I don't know if that's true, but FWIW the preamble tactic seems to work very well.

2. An 'antislop entry,' weighing in at ~250 tokens.

3. An 'agency' entry that may or may not matter at all.  It makes me feel better, though, just a few lines reminding the LLM that {{user}} is not special, and instructing it to maintain absolute moral neutrality.

4. Added an extra 'role' toggle, as an alternative to the default 'roleplayer' role.  This isn't a big deal.  Some people swear that LLMs write better in the 'writer' role.  Some even insist that if you have the word 'roleplay' anywhere in your prompt, the prose will degrade.  I can't say I've ever noticed either phenomenon.  But it doesn't hurt to have the option.  In this case, the change to the prompt is as bare bones as possible.

5. I did add a POV/Tense entry in the ROLE toggle, because that's where the original author had his 'style guide,' and I do think tense/POV deserves to be at the top of the prompt if you care about that sort of thing.  My preference is for second-person narration in present tense, so that's what you'll find, but easy enough to change.

6. Oh, and I commented out the bit about not impersonating the user's character.  I left in the prohibition against spoofing {{user}}'s dialogue, because that bothers me much more.  Matter of preference, but I like to leave the model some latitude to paraphrase/interpret {{user}}'s actions/responses.  

I think that's everything, or near enough.
