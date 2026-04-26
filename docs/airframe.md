## Airframe Design (CAD Model Explanation)

The airframe of the solar-powered glider is designed using Autodesk Fusion 360 to create an accurate and scalable 3D model. The design is divided into three main sections: fuselage, wings, and tail assembly.

---

### Fuselage

The fuselage is modeled as a streamlined body using extrusion from a side-profile sketch. It is designed to reduce aerodynamic drag while providing sufficient internal space for key components such as the flight controller, battery, and wiring.

Internal compartments are incorporated to:

* Securely mount electronics
* Protect components
* Maintain structural strength

---

### Wings

The wings are designed on the top plane and shaped to approximate an airfoil profile. A long wingspan with moderate chord length is selected to improve lift and gliding efficiency.

Key features:

* Symmetrical design using mirroring
* Flat upper surface sections for solar panel mounting
* Lightweight structure for better endurance

---

### Tail Assembly

The tail assembly consists of:

* **Horizontal stabilizer** → provides pitch stability
* **Vertical stabilizer** → provides yaw stability

These are modeled as thin aerodynamic surfaces attached to the rear of the fuselage.

---

### Control Surfaces

Control surfaces are defined by splitting sections of the wing and tail geometry:

* Ailerons → roll control
* Elevator → pitch control
* Rudder → yaw control

These sections represent movable parts actuated by servo motors in the physical system.

---

### Component Integration

The CAD model includes designated mounting positions for:

* Pixhawk
* Battery
* Servo motors
* Brushless motor (rear pusher configuration)
* Solar panels mounted on wing surfaces

Proper spacing and alignment are maintained to achieve a stable center of gravity and balanced weight distribution.

---

### Assembly and Export

All components are combined into a complete assembly within the CAD environment. The final model can be exported in standard formats:

* STEP (.step) → for engineering and sharing
* STL (.stl) → for 3D printing

---

### Design Objective

The primary objective of the CAD-based airframe design is to ensure accuracy, repeatability, and ease of modification. This approach supports efficient prototyping and enables future upgrades such as AI modules and additional sensors.
