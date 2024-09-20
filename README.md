**Better Performance:**

ConstraintLayout :
It is more optimized for performance because it avoids multiple layout passes,
which often occur with deeply nested views in RelativeLayout.

RelativeLayout : Complex hierarchies often result in nested layouts -> slow down rendering
Nested layouts are avoided by providing a  flatter view hierarchy, which speeds up layout rendering.

**Flattened Layout Hierarchy:** nesting by allowing all views to be directly connected to each other or the parent.

**Consistency Across Different Screen Sizes:**
With ConstraintLayout, you can ensure layouts adapt to various screen sizes without needing multiple layout files,
unlike RelativeLayout.

**Percentage Positioning**

ConstraintLayout allows you to define constraints and positions in percentage terms, which is useful for responsive design across various screen sizes.
In RelativeLayout, percentage positioning is not natively supported, and achieving similar behavior usually requires custom logic.
