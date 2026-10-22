Game artwork for the home page cards.

  steal-an-egg.jpg   -> the Steal an Egg card

Square or near-square images render best (the card shows them at
144x144 with object-cover, so anything 300px+ on the short side is
plenty). Keep them as .jpg unless you need transparency — a photo
saved as .png is usually several times larger for no benefit.

If you change a file name, update the matching `image` value in
src/lib/site.ts. Setting it to `null` makes the card show a
styled placeholder instead.
