# cat-moment-clarity

Ranks cat pictures by **clarity of moment** — how precisely and completely each image captures its subject as the definitive version of that instant, rather than merely an approximation.

## Overview

There is a difference between a cat picture and *the* cat picture. You take forty photos of a cat doing something remarkable, and thirty-nine are disposable. Then there is the one where everything locks into place — the expression is legible, the composition is clean, the timing is perfect. That image doesn't just document the moment; it becomes the moment.

This function identifies those images. It does not evaluate cuteness, aesthetic style, breed, or photographic technique in the abstract. It asks one question: **does this image feel like the final, distilled version of its moment, or does it feel like a draft?**

## Input

The function accepts an array of cat pictures (minimum 2). Each element is an image in which a cat is the primary subject.

```
[image, image, image, ...]
```

- No metadata, captions, or context required
- Images may vary in content: kittens asleep, cats leaping, close-ups mid-yawn, cats in boxes
- Subject matter is not the point of evaluation — what matters is how the image handles its subject
- A mundane scene with total clarity of moment ranks above a spectacular scene captured poorly

## Output

A vector of scores, one per input image, representing each image's overall clarity of moment. Higher scores indicate images that feel more definitive — sharp, distilled, and sticky. Lower scores indicate images that feel approximate — cluttered, mistimed, ambiguous, or forgettable.

## What It Evaluates

The function evaluates three distinct qualities. Each captures a different dimension of what makes an image feel definitive. No single quality is sufficient on its own; an image must succeed across all three to achieve true clarity of moment.

### 1. Emotional Readability

How instantly and unambiguously the cat's expression communicates its state.

- **Evaluates:** The cat's face, eyes, posture, gesture, and body language
- **High score:** The viewer immediately knows what the cat is feeling or doing — the emotional signal is loud, vivid, and coherent
- **Low score:** The cat's state is ambiguous or muddled — a viewer would have to guess whether it is startled or calm, playful or annoyed
- **Key principle:** Applies equally to dramatic expressions and quiet stillness; what matters is that the message arrives without static

### 2. Compositional Focus

How effectively the image directs the viewer's eye to exactly the right place.

- **Evaluates:** Framing, background, visual hierarchy, angle, cropping, and the presence or absence of clutter
- **High score:** The eye lands on the subject — on the specific detail that matters — without wandering, searching, or sorting through distractions
- **Low score:** The image asks the viewer to do interpretive work: mentally crop, filter out clutter, or figure out where the point of the image lives
- **Key principle:** Does not require minimalism; a busy scene can have perfect focus if the elements funnel the eye to the right place

### 3. Temporal Precision

Whether the moment was captured at its exact peak — not a fraction too early or too late.

- **Evaluates:** The perfection of the captured instant, and the absence of blur or motion artifacts that obscure it
- **High score (frozen miracle):** Action caught at its apex — a paw mid-swat, a cat at the top of a leap, a tongue at the perfect angle of a blep
- **High score (eternal stillness):** A cat so completely at rest the image feels timeless, as though the moment has no beginning or end
- **Low score:** The image was taken a beat too early (action hasn't cohered) or too late (action has begun to dissolve), or blur prevents the moment from registering
- **Key principle:** Both forms — impossible precision and natural timelessness — are equally valid paths to a high score

## Use Cases

- **Content curation:** Surface the cat pictures that will stop a thumb mid-scroll — the ones that imprint rather than wash past
- **Pet photography:** Find the keepers among hundreds of nearly identical frames from a single session
- **Contests and communities:** Rank cat photography submissions on criteria that go beyond popularity or technical quality
- **Personal camera rolls:** Understand why one picture of your cat feels so much more satisfying than another taken three seconds later
- **Social media selection:** Identify which images have the authority and clarity to become the definitive post

## Philosophy

This function does not judge beauty, does not prefer one breed or color over another, and does not reward spectacle for its own sake. It asks only whether an image has achieved clarity — whether it has distilled its moment into something sharp, immediate, and permanent. The distinction it draws is between images you glance at and images that stick: the definitive versus the forgettable.