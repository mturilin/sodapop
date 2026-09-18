# How to Think When You Don’t Know

*This essay started with a simple question: could the useful ideas in Annie Duke’s* Thinking in Bets *have been expressed more crisply than they are in a full book? The goal here is to distill the core framework for making decisions under uncertainty into a tighter long-form essay—keeping the ideas that matter, stripping away repetition, and extending the framework where it becomes more useful in practice.*

Most important decisions have to be made before the facts are available. You hire someone before you know whether they will perform. You launch a product before you know whether customers will care. You invest before you know what the market will do. You choose a treatment before you know whether it will work. You make a strategic commitment before you know what competitors will do next.

Then reality arrives, and the mind begins rewriting history.

A product succeeds, so the strategy suddenly seems obvious. An investment loses money, so the decision seems foolish. A candidate becomes a star, so the interview process appears validated. A risky shortcut works, so the risk looks smaller in retrospect. We naturally use the outcome to tell ourselves a story about the quality of the decision that came before it.

That is the central problem. Decisions are made under uncertainty, but outcomes are observed with certainty. If we judge the first entirely through the second, we become bad students of our own experience.

The useful idea behind thinking in bets is that a decision should be evaluated using the information that was available when the decision was made. An outcome is evidence, but it is not a verdict. A good decision can produce a bad outcome because the world contains randomness. A bad decision can produce a good outcome for the same reason.

Once you take that distinction seriously, a whole set of practical habits follows: express beliefs in probabilities, identify the assumptions carrying most of the risk, update when new evidence arrives, size bets according to downside and reversibility, and keep enough records that you can learn from outcomes without rewriting the past.

## Decisions are bets on uncertain futures

Calling a decision a “bet” can sound more dramatic than it is. It simply means that every meaningful choice commits resources to one possible future while giving up alternatives. Hiring one person means not hiring another. Building feature A means feature B waits. Expanding into one market consumes capital and attention that could have gone somewhere else.

Every important decision therefore contains an implicit statement: *I believe this future is sufficiently likely, and sufficiently valuable, that I am willing to act on it.*

The difficulty is that people rarely make the bet explicit. We compress a bundle of assumptions into a sentence such as “this product will work,” “this candidate is strong,” or “this market is attractive.” Those statements sound clear, but they hide the actual structure of the decision.

Take a company deciding whether to launch an AI coding product. The apparent question is whether the product will succeed. Underneath that are many separate beliefs: developers must have a painful enough problem; the model must solve enough of that problem; the product must become reliable enough to earn trust; distribution must work; competitors must not erase the advantage too quickly; and the economics must eventually make sense.

The first useful move is to unpack the bet. Ask what has to be true for the decision to work, and then ask which of those things is both important and uncertain. Usually one or two assumptions carry much more of the risk than the rest.

This is where decision-making starts to become practical. If the entire business depends on whether customers will pay $100 per month, the most valuable work may be testing willingness to pay. If technical feasibility is the real uncertainty, market research will not help much. If success depends on a distribution partnership, polishing product details may be premature.

The point is to locate the load-bearing assumptions. Once they are visible, uncertainty becomes something you can often reduce rather than merely discuss.

## Replace certainty with probability

People are naturally drawn to categorical language. “This will work.” “She’s a strong candidate.” “We’ll ship in June.” “The competitor won’t catch us.” The world usually does not deserve that level of certainty.

A better habit is to attach rough probabilities to important beliefs. “I think there is a 70% chance we reach 100,000 weekly users within a year” is a much more useful statement than “I think customers will adopt it.” The number does not need to be scientifically precise. Its value is that it forces you to reveal how strongly you actually believe the claim.

This matters because ordinary language hides enormous differences. Two executives may both say that a project is “likely to succeed,” while one means 55% and the other means 90%. They appear to agree until someone asks for a number.

Probability also makes a belief easier to inspect. If you say 70%, someone can reasonably ask why. Which evidence pushed you above 50%? Which assumptions are doing most of the work? What would move you to 80%? What would push you down to 40%?

That changes the quality of disagreement. Instead of arguing over conclusions, people can compare the models producing those conclusions.

This is close to the spirit of Bayesian reasoning, even if you never write down Bayes’ theorem. You begin with a prior belief, observe evidence, and update. The essential discipline is not the mathematics. It is the willingness to let your beliefs move.

Suppose you believe there is a 70% chance that a new product will succeed. Early customer testing then goes badly. The wrong response is to search immediately for reasons the evidence “doesn’t count.” Maybe the sample really is too small. Maybe the customers were unrepresentative. But those explanations should themselves be tested rather than used as automatic defenses.

The better question is: *How much should this evidence change my probability?*

If your original thesis depended on customers understanding the product immediately, repeated confusion should move your belief substantially. If the thesis never assumed instant comprehension, the same evidence should matter less. Updating is not simply reacting to bad news; it is asking how surprising the evidence would be if your current model were correct.

This is also why changing your mind should not be treated as embarrassment. In an uncertain environment, a belief that never changes is often a sign that evidence is not getting through.

## Separate uncertainty from ignorance

“We don’t know” can mean several very different things, and each calls for a different response.

Sometimes uncertainty is irreducible. You can know everything reasonably knowable about a fair coin toss and still not know which side will land up. Sometimes the uncertainty comes from missing information that could be collected. Sometimes it comes from a weak model: you have plenty of data but do not understand the mechanism well enough to predict what happens. And sometimes “we don’t know” simply means that nobody has done the work.

These cases matter because organizations often respond to all uncertainty with more analysis. Another deck appears. Another forecast gets built. Another market model is produced. The decimal places multiply, but the uncertainty does not shrink.

A better question is: *Which uncertainty can I reduce, and which uncertainty must I live with?*

If the missing information is cheap to obtain and likely to change the decision, gather it. If the uncertainty is fundamentally irreducible, additional analysis may have little value. If the model is weak, run an experiment that reveals something about the underlying mechanism.

This leads naturally to the idea of value of information. Before doing more research, ask whether the information could realistically change what you do. If the answer is no, then analysis has become a form of delay.

The amount of analysis should scale with the stakes, the uncertainty, the reversibility of the decision, and the cost of learning more. Choosing between two restaurants does not deserve three hours of research. Acquiring a company for several billion dollars probably does.

## Size the bet, not just the belief

Probability alone is not enough. A decision also depends on the value and danger of the possible outcomes.

A 90% chance of gaining one dollar and a 10% chance of losing a million dollars is obviously unattractive. A lower-probability opportunity can be compelling if the upside is large and the downside is contained.

Expected value gives a simple language for thinking about this. Imagine one option with a 90% chance of gaining $10 and a 10% chance of losing $10. Its expected value is $8. Another option has a 20% chance of gaining $1,000 and an 80% chance of losing $20. Its expected value is $184. The second choice is far less likely to produce a win on any single attempt, yet it has much higher expected value.

Real decisions are messier than this, but the framework forces two separate questions: how likely is each outcome, and how much does each outcome matter?

There is an important complication. Expected value is most useful when you can survive the downside and continue playing. A casino can tolerate losing individual hands because the game repeats thousands of times. A person cannot use the same reasoning for a bet that has a small chance of financial ruin.

This is why good decision-making has to include survival. A strategy can look attractive on average and still be unacceptable if one plausible outcome destroys your ability to benefit from future opportunities. Investors handle this through position sizing and limits on leverage. Companies hold cash reserves. Engineers build redundancy into systems. The forms differ, but the logic is the same: protect the ability to keep playing.

Reversibility matters for the same reason. When uncertainty is high, small bets are usually better than large ones. Prototype before building the factory. Pilot with one team before rolling out company-wide. Spend $10,000 before spending $10 million. Early decisions should often be designed to buy information cheaply.

As evidence accumulates, commitment can increase. This is one of the most useful ways to think about strategy under uncertainty: not as a single giant decision, but as a sequence of bets whose size grows with confidence.

## Disagreement is information

When intelligent people disagree, the disagreement itself can be useful evidence.

Suppose you believe an acquisition has a 75% chance of succeeding and a colleague you respect says 35%. The instinctive response is to begin defending your view. A better response is to ask what the other person knows, assumes, or values differently.

Perhaps you agree that the technology is complementary but disagree about integration risk. Perhaps you agree on the facts but weight them differently. Perhaps one of you has information the other lacks. Perhaps you are actually optimizing for different outcomes.

Once the disagreement is decomposed, the discussion becomes much more productive. “Good acquisition versus bad acquisition” may turn into a narrower and testable question such as: *How likely is organizational integration to succeed?*

This works best when beliefs are not treated as identity. If an idea becomes “Sarah’s strategy” or “Daniel’s architecture,” criticism of the idea can feel like criticism of the person. People then become motivated to defend their previous position rather than improve it.

It is healthier to talk about hypotheses: the enterprise-sales hypothesis, the event-driven architecture hypothesis, the assumption that customers will pay for premium support. The goal is to make it socially easier to say, “The evidence is moving against this hypothesis.”

One particularly useful question is: *What would change your mind?* If the answer is “nothing,” the conversation is no longer about evidence.

For important projects, this question can be made concrete in advance. What observation would make you reduce investment, change direction, or stop entirely? If you define those thresholds before emotional and organizational attachment grows, you are less likely to keep rationalizing a failing thesis later.

## Learn from outcomes without fooling yourself

The hardest part comes after the decision, because outcomes are vivid and memory is unreliable.

Suppose a project succeeds. You will be tempted to remember yourself as more confident than you really were. If it fails, the warning signs will seem more obvious in retrospect. This is hindsight bias, and it makes experience much less educational than it appears.

The specific error of judging a decision mainly by its outcome is sometimes called *resulting*. If Anna puts all her money into a random cryptocurrency because someone at a party says it will double, and it does, she got a good outcome from a bad process. If Ben builds a diversified portfolio after careful analysis and the market crashes the next month, he got a bad outcome from a much better process.

The distinction seems obvious when the example is exaggerated. In real life, the line is harder to hold because outcomes dominate attention.

A decision journal is one of the simplest defenses. Before an important decision, write down what you believe, your rough confidence, the assumptions that matter, the major upside and downside, what evidence would prove you wrong, and what you expect to happen. Then revisit the entry later.

The point is not bureaucratic documentation. It is to preserve the state of your mind before hindsight rewrites it.

Over time, the journal becomes a record of your own calibration. Maybe you repeatedly underestimate execution time. Maybe you overestimate the reliability of partnerships. Maybe you are unusually good at judging technical feasibility. Maybe organizational resistance surprises you again and again.

This turns decision-making into something that can actually improve.

Calibration is especially useful because it provides a rough way to test judgment. If you make many predictions at 70% confidence, about 70% of them should eventually be correct. If 95% are correct, you are probably underconfident. If 45% are correct, you are overconfident.

No single prediction tells you much. A sequence does.

That is another reason not to overlearn from one success or failure. A venture investor expects many investments to fail. A product leader expects some experiments to produce negative results. A doctor expects some treatments not to work. The quality of the process becomes visible across many decisions, not one dramatic outcome.

## A practical way to make an uncertain decision

For an important decision, most of this framework can be reduced to a short set of questions:

- What exactly am I deciding, and what alternatives am I giving up?
- What outcomes matter, and roughly how likely is each one?
- What has to be true for this decision to work?
- Which assumption carries the most risk or uncertainty?
- What information could materially change my view?
- Can I test the key uncertainty with a smaller, more reversible bet?
- What downside could threaten my ability to continue?
- What evidence would make me change direction or stop?
- What do I predict will happen, and how confident am I?

Writing down the answers is often enough to expose sloppy thinking. It becomes obvious when a conclusion rests on an assumption nobody has examined, when a probability is mostly intuition dressed up as certainty, or when a team is spending weeks gathering information that is unlikely to change the decision.

Then make the decision.

Later, when the outcome is known, resist the urge to ask only whether you won. Ask whether the bet made sense given what was knowable at the time. Ask which assumptions were wrong. Ask which parts of the outcome were skill and which were luck. Ask what should change in your model before the next decision.

## The deeper habit

The broader lesson is that good judgment is not the ability to predict the future with certainty. Nobody can do that consistently. It is the ability to represent uncertainty honestly enough that you can act well despite it.

That means separating the quality of a decision from the quality of its outcome. It means replacing vague confidence with rough probabilities, making assumptions explicit, updating when evidence arrives, and sizing commitments so that uncertainty does not become fatal. It also means recording enough of your thinking that reality can teach you something later.

The world rarely gives you the information you want before it demands a decision. So the practical goal is not certainty. It is to make the best bet available, observe what happens, update your model, and make the next bet from a slightly better understanding of the world.
