# Run-length encoding demo
Demo of efficient run-length encoding for solid colours

When putting images on the web, the rule of thumb is: use JPG for phtographic images, and PNG for generated ones with large areas of solid color (typically computer-generated).

**JPG** uses destructive, perception-specific compression which looks good even when slightly distorded compared to the original.

**PNG** and GIF use run-length encoding, which can efficiently pack those large areas into a few numbers.
