---
hide:
  - toc
---

<!-- https://steamcommunity.com/sharedfiles/filedetails/?id=2955664375 -->

![transform](./image/transform.png)


### If the cursor is inside the transformation area

You can move it freely by clicking.

![transform_move](./image/transform_move.gif)

You can move it only horizontally or only vertically by Shift + clicking.

![transform_move_shift](./image/transform_move_shift.gif)


### If the cursor is outside the transformation area

You can rotate it by clicking.

![transform_rotate](./image/transform_rotate.gif)

You can rotate it around the anchor by Ctrl + clicking.

![transform_rotate_ctrl](./image/transform_rotate_ctrl.gif)


### If the cursor is on the anchor

You can move only the anchor by clicking.

![transform_anchor](./image/transform_anchor.gif)


### If the cursor is on the top, bottom, left, or right edge ( □ )

You can move the edge by clicking.

![transform_edge](./image/transform_edge.gif)

You can move both sides at the same time without moving the center position by Alt + clicking.

![transform_edge_alt](./image/transform_edge_alt.gif)

You can move the edge freely by Ctrl + clicking.

![transform_edge_ctrl](./image/transform_edge_ctrl.gif)

You can move the edge along its direction by Ctrl + Shift + clicking.

![transform_edge_ctrlShift](./image/transform_edge_ctrlShift.gif)


### If the cursor is on 4 vertices ( □ )

You can move the vertex by clicking.

![transform_vert](./image/transform_vert.gif)

You can scale and rotate it with Alt + clicking.

![transform_vert_alt](./image/transform_vert_alt.gif)

You can scale it uniformly by Shift + clicking.

![transform_vert_shift](./image/transform_vert_shift.gif)

You can scale it uniformly without moving the center position by Shift + Alt + clicking.

![transform_vert_shiftAlt](./image/transform_vert_shiftAlt.gif)

---

You can move only the vertex freely by Ctrl + clicking. <br />
In this case, the appearance changes in three ways.

#### Ctrl + clicking in "Transform"

![transform_vert_ctrl](./image/transform_vert_ctrl.gif)

#### Ctrl + clicking in "Perspective transform" with "Perspective" turned off

![transform_persp_off_vert_ctrl](./image/transform_persp_off_vert_ctrl.gif)

#### Ctrl + clicking in "Perspective transform" with "Perspective" turned on

![transform_persp_on_vert_ctrl](./image/transform_persp_on_vert_ctrl.gif)


You can return to the state before transform by pressing the __"Reset"__ button.

* Transform(canvas size)
* Move Scale Rotate(canvas size)
* Perspective transform
* Liquify filter
* Retouch filter

These five methods can save transform contents. <br />
If saved, you can apply the same transform to another layer.

If you want to transform by specifying a numerical value, please use __"Move Scale Rotate"__. <br />
For example, if you want to scale it down to 50 % or rotate it by 45 degrees.
