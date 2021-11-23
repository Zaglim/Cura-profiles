# RETIRED
I now use and recommend [SuperSlicer](https://github.com/supermerill/SuperSlicer.git)!
I use SuperSlicer over Cura for these reasons: (Note I think most of these apply to it's ancestors PrusaSlicer and Slic3r as well):
- Object level settings when printing multiple objects at once:
  - Adaptive layer height is not applied globally
  - Set different perimeter count, shell thickness, etc for each object
- Cutting corners feature minimizes corner bulge
- Paint on supports - only support where you want to
- Double ironing! I don't think it's benificial if you're ironing is well tuned but I use it anyway :)
- Internal bridge under top shell. This I think is superior to cura's (excellent) gradual infill steps feature, because that can have anchoring issues.




## Cura-profiles
My main cura profiles (settings)

### Most commonly changed settings
- Toggling support on/off					(overhang quality vs time and material cost)
- Adaptive layers topography size			(overhang quality vs time)
- extra infill wall count					(strength vs time & material cost/weight)
- iron spacing								(surface quality vs time)
- outer wall acceleration					(corner sharpness vs time)
