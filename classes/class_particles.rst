.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the Particles.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_Particles:

Particles
=========

**Inherits:** :ref:`GeometryInstance<class_geometryinstance>` **<** :ref:`VisualInstance<class_visualinstance>` **<** :ref:`Spatial<class_spatial>` **<** :ref:`Node<class_node>` **<** :ref:`Object<class_object>`

**Category:** Core

Brief Description
-----------------

3D particle emitter.

Member Functions
----------------

+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Rect3<class_rect3>`        | :ref:`capture_aabb<class_Particles_capture_aabb>` **(** **)** const                                                                |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`            | :ref:`get_amount<class_Particles_get_amount>` **(** **)** const                                                                    |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`            | :ref:`get_draw_order<class_Particles_get_draw_order>` **(** **)** const                                                            |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Mesh<class_mesh>`          | :ref:`get_draw_pass_mesh<class_Particles_get_draw_pass_mesh>` **(** :ref:`int<class_int>` pass **)** const                         |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`            | :ref:`get_draw_passes<class_Particles_get_draw_passes>` **(** **)** const                                                          |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`        | :ref:`get_explosiveness_ratio<class_Particles_get_explosiveness_ratio>` **(** **)** const                                          |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`            | :ref:`get_fixed_fps<class_Particles_get_fixed_fps>` **(** **)** const                                                              |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`          | :ref:`get_fractional_delta<class_Particles_get_fractional_delta>` **(** **)** const                                                |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`        | :ref:`get_lifetime<class_Particles_get_lifetime>` **(** **)** const                                                                |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`          | :ref:`get_one_shot<class_Particles_get_one_shot>` **(** **)** const                                                                |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`        | :ref:`get_pre_process_time<class_Particles_get_pre_process_time>` **(** **)** const                                                |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Material<class_material>`  | :ref:`get_process_material<class_Particles_get_process_material>` **(** **)** const                                                |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`        | :ref:`get_randomness_ratio<class_Particles_get_randomness_ratio>` **(** **)** const                                                |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`        | :ref:`get_speed_scale<class_Particles_get_speed_scale>` **(** **)** const                                                          |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`          | :ref:`get_use_local_coordinates<class_Particles_get_use_local_coordinates>` **(** **)** const                                      |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Rect3<class_rect3>`        | :ref:`get_visibility_aabb<class_Particles_get_visibility_aabb>` **(** **)** const                                                  |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`          | :ref:`is_emitting<class_Particles_is_emitting>` **(** **)** const                                                                  |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`restart<class_Particles_restart>` **(** **)**                                                                                |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_amount<class_Particles_set_amount>` **(** :ref:`int<class_int>` amount **)**                                             |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_draw_order<class_Particles_set_draw_order>` **(** :ref:`int<class_int>` order **)**                                      |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_draw_pass_mesh<class_Particles_set_draw_pass_mesh>` **(** :ref:`int<class_int>` pass, :ref:`Mesh<class_mesh>` mesh **)** |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_draw_passes<class_Particles_set_draw_passes>` **(** :ref:`int<class_int>` passes **)**                                   |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_emitting<class_Particles_set_emitting>` **(** :ref:`bool<class_bool>` emitting **)**                                     |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_explosiveness_ratio<class_Particles_set_explosiveness_ratio>` **(** :ref:`float<class_float>` ratio **)**                |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_fixed_fps<class_Particles_set_fixed_fps>` **(** :ref:`int<class_int>` fps **)**                                          |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_fractional_delta<class_Particles_set_fractional_delta>` **(** :ref:`bool<class_bool>` enable **)**                       |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_lifetime<class_Particles_set_lifetime>` **(** :ref:`float<class_float>` secs **)**                                       |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_one_shot<class_Particles_set_one_shot>` **(** :ref:`bool<class_bool>` enable **)**                                       |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_pre_process_time<class_Particles_set_pre_process_time>` **(** :ref:`float<class_float>` secs **)**                       |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_process_material<class_Particles_set_process_material>` **(** :ref:`Material<class_material>` material **)**             |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_randomness_ratio<class_Particles_set_randomness_ratio>` **(** :ref:`float<class_float>` ratio **)**                      |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_speed_scale<class_Particles_set_speed_scale>` **(** :ref:`float<class_float>` scale **)**                                |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_use_local_coordinates<class_Particles_set_use_local_coordinates>` **(** :ref:`bool<class_bool>` enable **)**             |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_visibility_aabb<class_Particles_set_visibility_aabb>` **(** :ref:`Rect3<class_rect3>` aabb **)**                         |
+----------------------------------+------------------------------------------------------------------------------------------------------------------------------------+

Member Variables
----------------

  .. _class_Particles_amount:

- :ref:`int<class_int>` **amount** - Number of particles to emit.

  .. _class_Particles_draw_order:

- :ref:`int<class_int>` **draw_order** - Particle draw order. Uses ``DRAW_ORDER\_\*`` values. Default value: ``DRAW_ORDER_INDEX``.

  .. _class_Particles_draw_pass_1:

- :ref:`Mesh<class_mesh>` **draw_pass_1**

  .. _class_Particles_draw_pass_2:

- :ref:`Mesh<class_mesh>` **draw_pass_2**

  .. _class_Particles_draw_pass_3:

- :ref:`Mesh<class_mesh>` **draw_pass_3**

  .. _class_Particles_draw_pass_4:

- :ref:`Mesh<class_mesh>` **draw_pass_4**

  .. _class_Particles_draw_passes:

- :ref:`int<class_int>` **draw_passes**

  .. _class_Particles_emitting:

- :ref:`bool<class_bool>` **emitting** - If ``true`` particles are being emitted. Default value: ``true``.

  .. _class_Particles_explosiveness:

- :ref:`float<class_float>` **explosiveness** - Time ratio between each emission. If ``0`` particles are emitted continuously. If ``1`` all particles are emitted simultaneously. Default value: ``0``.

  .. _class_Particles_fixed_fps:

- :ref:`int<class_int>` **fixed_fps**

  .. _class_Particles_fract_delta:

- :ref:`bool<class_bool>` **fract_delta**

  .. _class_Particles_lifetime:

- :ref:`float<class_float>` **lifetime** - Amount of time each particle will exist. Default value: ``1``.

  .. _class_Particles_local_coords:

- :ref:`bool<class_bool>` **local_coords** - If ``true`` particles use the parent node's coordinate space. If ``false`` they use global coordinates. Default value: ``true``.

  .. _class_Particles_one_shot:

- :ref:`bool<class_bool>` **one_shot** - If ``true`` only ``amount`` particles will be emitted. Default value: ``false``.

  .. _class_Particles_preprocess:

- :ref:`float<class_float>` **preprocess**

  .. _class_Particles_process_material:

- :ref:`Material<class_material>` **process_material** - :ref:`Material<class_material>` for processing particles. Can be a :ref:`ParticlesMaterial<class_particlesmaterial>` or a :ref:`ShaderMaterial<class_shadermaterial>`.

  .. _class_Particles_randomness:

- :ref:`float<class_float>` **randomness** - Emission randomness ratio. Default value: ``0``.

  .. _class_Particles_speed_scale:

- :ref:`float<class_float>` **speed_scale** - Speed scaling ratio. Default value: ``1``.

  .. _class_Particles_visibility_aabb:

- :ref:`Rect3<class_rect3>` **visibility_aabb**


Numeric Constants
-----------------

- **DRAW_ORDER_INDEX** = **0** --- Particles are drawn in the order emitted.
- **DRAW_ORDER_LIFETIME** = **1** --- Particles are drawn in order of remaining lifetime.
- **DRAW_ORDER_VIEW_DEPTH** = **2** --- Particles are drawn in order of depth.
- **MAX_DRAW_PASSES** = **4**

Description
-----------

3D particle node used to create a variety of particle systems and effects. ``Particles`` features an emitter that generates some number of particles at a given rate.

Use the ``process_material`` property to add a :ref:`ParticlesMaterial<class_particlesmaterial>` to configure particle appearance and behavior. Alternatively, you can add a :ref:`ShaderMaterial<class_shadermaterial>` which will be applied to all particles.

Member Function Description
---------------------------

.. _class_Particles_capture_aabb:

- :ref:`Rect3<class_rect3>` **capture_aabb** **(** **)** const

.. _class_Particles_get_amount:

- :ref:`int<class_int>` **get_amount** **(** **)** const

.. _class_Particles_get_draw_order:

- :ref:`int<class_int>` **get_draw_order** **(** **)** const

.. _class_Particles_get_draw_pass_mesh:

- :ref:`Mesh<class_mesh>` **get_draw_pass_mesh** **(** :ref:`int<class_int>` pass **)** const

.. _class_Particles_get_draw_passes:

- :ref:`int<class_int>` **get_draw_passes** **(** **)** const

.. _class_Particles_get_explosiveness_ratio:

- :ref:`float<class_float>` **get_explosiveness_ratio** **(** **)** const

.. _class_Particles_get_fixed_fps:

- :ref:`int<class_int>` **get_fixed_fps** **(** **)** const

.. _class_Particles_get_fractional_delta:

- :ref:`bool<class_bool>` **get_fractional_delta** **(** **)** const

.. _class_Particles_get_lifetime:

- :ref:`float<class_float>` **get_lifetime** **(** **)** const

.. _class_Particles_get_one_shot:

- :ref:`bool<class_bool>` **get_one_shot** **(** **)** const

.. _class_Particles_get_pre_process_time:

- :ref:`float<class_float>` **get_pre_process_time** **(** **)** const

.. _class_Particles_get_process_material:

- :ref:`Material<class_material>` **get_process_material** **(** **)** const

.. _class_Particles_get_randomness_ratio:

- :ref:`float<class_float>` **get_randomness_ratio** **(** **)** const

.. _class_Particles_get_speed_scale:

- :ref:`float<class_float>` **get_speed_scale** **(** **)** const

.. _class_Particles_get_use_local_coordinates:

- :ref:`bool<class_bool>` **get_use_local_coordinates** **(** **)** const

.. _class_Particles_get_visibility_aabb:

- :ref:`Rect3<class_rect3>` **get_visibility_aabb** **(** **)** const

.. _class_Particles_is_emitting:

- :ref:`bool<class_bool>` **is_emitting** **(** **)** const

.. _class_Particles_restart:

- void **restart** **(** **)**

.. _class_Particles_set_amount:

- void **set_amount** **(** :ref:`int<class_int>` amount **)**

.. _class_Particles_set_draw_order:

- void **set_draw_order** **(** :ref:`int<class_int>` order **)**

.. _class_Particles_set_draw_pass_mesh:

- void **set_draw_pass_mesh** **(** :ref:`int<class_int>` pass, :ref:`Mesh<class_mesh>` mesh **)**

.. _class_Particles_set_draw_passes:

- void **set_draw_passes** **(** :ref:`int<class_int>` passes **)**

.. _class_Particles_set_emitting:

- void **set_emitting** **(** :ref:`bool<class_bool>` emitting **)**

.. _class_Particles_set_explosiveness_ratio:

- void **set_explosiveness_ratio** **(** :ref:`float<class_float>` ratio **)**

.. _class_Particles_set_fixed_fps:

- void **set_fixed_fps** **(** :ref:`int<class_int>` fps **)**

.. _class_Particles_set_fractional_delta:

- void **set_fractional_delta** **(** :ref:`bool<class_bool>` enable **)**

.. _class_Particles_set_lifetime:

- void **set_lifetime** **(** :ref:`float<class_float>` secs **)**

.. _class_Particles_set_one_shot:

- void **set_one_shot** **(** :ref:`bool<class_bool>` enable **)**

.. _class_Particles_set_pre_process_time:

- void **set_pre_process_time** **(** :ref:`float<class_float>` secs **)**

.. _class_Particles_set_process_material:

- void **set_process_material** **(** :ref:`Material<class_material>` material **)**

.. _class_Particles_set_randomness_ratio:

- void **set_randomness_ratio** **(** :ref:`float<class_float>` ratio **)**

.. _class_Particles_set_speed_scale:

- void **set_speed_scale** **(** :ref:`float<class_float>` scale **)**

.. _class_Particles_set_use_local_coordinates:

- void **set_use_local_coordinates** **(** :ref:`bool<class_bool>` enable **)**

.. _class_Particles_set_visibility_aabb:

- void **set_visibility_aabb** **(** :ref:`Rect3<class_rect3>` aabb **)**


