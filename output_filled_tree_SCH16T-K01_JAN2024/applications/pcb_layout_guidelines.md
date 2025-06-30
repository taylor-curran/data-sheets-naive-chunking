# PCB layout guidelines for SCH16T Series

**Source**: Page 52, Chunk 200  
**Category**: PCB layout guidelines for SCH16T Series  
**Chunk Index**: 200

---

• DRY_SYNC shall be left floating if these features are not used.
• N.C. pin 2 shall be left floating as indicated by schematic.
8.2 General application PCB layout
A PCB layout example of the SCH16T Series component is presented in Figure 18 Reference PCB
layout. The presented layout can be used as such or only as reference. When designing the PCB, it is
advised to follow general layout guidelines below:
• Connect SMD decoupling capacitors right next to the component on top layer.
• Each ground pin should be connected to the ground directly.
• Signal lines of this component (SCH16T series) can be freely routed under the component. It is
expected that signal lines of other components have also no effect on the SCH16T component,
but the user is advised to verify functionality before implementation.
• Keep all routing as low resistance as possible.
Murata Electronics Oy SCH16T Doc.No. 11624
www.murata.com Rev. 2

---

**AI Reasoning**: The content primarily provides guidelines for PCB layout specific to the SCH16T Series component, which falls under application-related information. The directory 'applications' is broad enough to encompass various usage scenarios and design considerations, making it a practical choice. The filename 'pcb_layout_guidelines.md' succinctly captures the essence of the content, focusing on the layout instructions provided.
