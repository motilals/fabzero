**Design and Fabrication of a programable electronic circuit**
The process will start with designing the electronic circuit and developing its PCB diagram by using **Kicad** software and then send it for milling.

The first step is to draw a schematic design of the circuit you are going to fabricate using a pcb design software such as **KICAD** 
 ![a schematic design of circuit](img/schema.jpg)

**1. To create a schematic diagram** 
- Open new project in Kicad
- Place components using **place component** tool and by choosing components from dropdown list

*For ease of working*

- **To move component** - place cursor over component and press G
- **To rotate component** - place cursor over component and press R
- **To duplicate component** - place cursor over component and press C
- **To delete component** - place cursor over component and press Del

- Connect components using **green wire icon** (tools on rt. hand)

- *Do not forget to attach a PWR_FLAG to Vcc and GND.*
- *Do not forget to assign a "no connect" symbol for unused pin of an IC.* 

**2. Annotation or Naming**
- Use "Annotate schematic symbols" tool (choose default values)

**3. To Edit Value of Components**
- Move cursor over component + press 'E'  (then type value)

**4. To write a local name / label**
- Use "place Net label" icon 

**5. To Generate Net List**
- Use "Generate Netlist" icon (choose default values)

**6. To Assign foot print**
- Use "Assign PCB footprints to schematic symbols" icon
![Assigning Footprints to components](img/footprint)



