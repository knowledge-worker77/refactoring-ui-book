# Working with colors

Hex codes and RGB values are the most commonly used formats for defining color codes for the web but they aren't the only options available.

Hue, Saturation, and Lightness or HSL for short, represents colors using attributes the human-eye intuitively. 

- The Hue is the colors position on the wheel.

- Saturation is how colorful or vivid a color looks.

- Lightness is just what it sounds like, it measures how close a color is to black or to white.

Ever used one of those color palette generators where you pick a starting color, tweak some options, and are then bestowed the five perfect colors you should use to build your website.

Well, you can’t build anything with five hex codes. To build something real, you need a much more comprehensive set of colors to choose from. You can break a good color palette down into three categories.

Greys for text, backgrounds, panels, and form controls. Primary color(s) Most sites need one, maybe two colors that are used for primary actions, active navigation elements, etc. Ultra-light shades can be useful as a tinted background for things like alerts, while darker shades work great for text and accent colors On top of primary colors, every site needs a few accent colors for communicating different things to the user.

When you need to create a lighter or darker variation of a color in your palette, don’t get clever using CSS pre-processor functions like “lighten” or “darken” to create shades on the fly.

Start by picking a base color for the scale you want to create the color in the middle that your lighter and darker shades are based on. The next thing is picking your darkest shade and your lightest shade.

The darkest shade of a color is usually reserved for text, while the lightest shade might be used to tint the background of an element. 

Color temperature makes a great difference in UI design. Yellowish orange hues will give your element a warm feeling. Blueish green hues will give our element a Cool feeling.

To make sure your designs are accessible, the Web Content Accessibility Guidelines (WCAG) recommend that normal text (under ~18px) has a contrast ratio of at least 4.5:1, and that larger text has a contrast ratio of at least 3:1. 

Color can be a fantastic way to enhance information and make it easier to understand, but be careful not to rely on it, or users with color blindness will have a hard time interpreting your UI. Always use color to support something that your design is already saying. never use it as the only means of communication.

## Adding Depth

To create a sense of depth in your designs you can use shadows and emulate a light source to emulate a sense of depth.

If top edge of the panel is lighter then the bottom then the light source is being emulated from the top. 

If you want an element to appear raised or inset, first figure out what profile you want that element to have, then mimic how a light source would interact with that shape.

Raising buttons is also a way to add depth, when the user click on it it gives the feel of being pressed and the color changes to lighter shade. Shadows can be more than just a flashy effect, if used thoughtfully, they let you position elements on a virtual z-axis to create a meaningful sense of depth.

Small shadows with a tight blur radius make an The closer something feels to the user, the more it will attract their focus. You might use a smaller shadow for something like a button, where you want the user to notice it but don’t want it to dominate the page

Just like with color, typography, spacing, and sizing, defining a fixed set of shadows will speed up your workflow and help maintain consistency in your designs. You don’t need a ton of different shadows five options is usually plenty.

Shadows aren’t only useful for positioning elements on the z-axis statically; they’re a great way to provide visual cues to the user as they interact with elements, too.

Combining shadows is not easy, but if done correctly it can give you more control than a single a shadow. The first shadow is larger and softer, with a considerable vertical offset and large blur radius. It simulates the shadow cast behind an object by a direct light source.

The second shadow is tighter and darker, with less of a vertical offset and a smaller blur radius. It simulates the shadowed area underneath an object where even ambient light has a hard time reaching. 

As an object gets further away from a surface, the small, dark shadow created by a lack of ambient light slowly disappears. So if you’re going to use this two-shadow technique in your own projects, make sure you make that shadow more subtle for shadows that represent a higher elevation.

One of the most effective ways to create depth is to overlap different elements to make it feel like a design has multiple layers. This technique can work great with images as well, but without special consideration it’s easy for overlapping images to clash.
