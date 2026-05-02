# Tripod
Tripod stand for Phone

## Voices & Requirements
- Primary Use: Indoor selfies and long time-lapses
- Versatility: Stable ground placement on flat surfaces
- Portability: Foldable design for easy packing and traveling
- Phone orientation: Portrait and Landscape capable
- Universal Fit: Capable of holding generic phone designs and multiple sizes
- Target Height: Up to 5 ft
- Height Adjustment: Must be easily adjustable
- Environment: Limited to flat surfaces; no harsh environment requirements
- Quick Release: Integrated quick release system for phone mounting
- Repairability: Modular design to allow easy 3D printing and replacement of broken components

## Tripod Head Requirements
- Functionality: Integrated tilting and rotational capabilities
- Locking: Ability to securely lock both tilt and rotation into a single position

## Stability Designs & Theories
- Three-point contact for guaranteed surface stability.
- Leg splay angle balance: Wider legs increase stability but increase stress on hinges.
- TBD

## Design Guide Summary
- **Hardware**: Use standard 1/4"-20 UNC threads for mounts; use metal inserts (heat-set or captive nuts) instead of printed plastic threads.
- **Materials**:
  - **Structural (Legs/Apex)**: PETG or ASA for toughness and UV resistance.
  - **Moving Parts**: Nylon for high-friction/wear areas.
  - **Grips/Feet**: TPU for non-slip and shock absorption.
- **Structure**: Prioritize high wall counts (perimeters) over high infill; use Gyroid or Cubic patterns for strength and vibration damping.
- **CAD**: Use modular assemblies (bolts/nuts) rather than print-in-place for better strength and repairability.
- **Tolerances**: 0.0-0.05mm for press fits, 0.05-0.1mm for close fits, and 0.4-0.5mm for sliding/rotating parts.
- **Mechanisms**:
  - **Locks**: Twist locks for low profile; Flip locks for visual confirmation and robustness.
  - **Heads**: Ball heads for speed; Pan-and-Tilt for precision.
  - **Clamps**: PETG/Polycarbonate for printed springs to avoid PLA creep.

## DFMEA

## CAD

## Product Design Drawings

## Manufacturing (3D Printing)
- Material: PLA (Potential upgrade to PETG if PLA is insufficient)
- Constraint: Preference for 100% 3D printed design without any additional metal parts

### Design for Manufacturing (DFM) Checklist
- [ ] Optimize print orientation to minimize supports
- [ ] Ensure wall thickness is a multiple of nozzle diameter (e.g., 0.4mm)
- [ ] Implement tolerances (0.2-0.4mm) for mating and moving parts
- [ ] Use fillets and chamfers to reduce stress concentrations and improve bed adhesion
- [ ] Avoid steep overhangs (>45°) to reduce support material
- [ ] Check for potential warping in large flat surface areas
- [ ] Evaluate assembly methods (snap-fits, threaded inserts, or screws)

## Technical Specifications
- Compatibility: TBD
- Ergonomics: TBD

## Observed Issues

## Future Scope
- Outdoor use

## Appendix
