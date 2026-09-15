# Awesome PCB Resources

A curated list of PCB design, manufacturing, PCBA, EMS, and electronics engineering resources.

## Contents

- [PCB Design](#pcb-design)
- [PCB Calculators](#pcb-calculators)
- [Engineering Tools](#engineering-tools)
- [PCB Manufacturing](#pcb-manufacturing)
- [PCB Assembly](#pcb-assembly)
- [EMS and Electronics Manufacturing](#ems-and-electronics-manufacturing)
- [DFM / DFA / DFT](#dfm--dfa--dft)
- [Component Sourcing](#component-sourcing)
- [Knowledge and Learning](#knowledge-and-learning)
- [Industry Resources](#industry-resources)

## PCB Design

- [KiCad](https://www.kicad.org/) - Open-source EDA suite for schematic capture, PCB layout, Gerber output, and manufacturing files.
- [LibrePCB](https://librepcb.org/) - Open-source EDA tool for schematic and PCB design.
- [EasyEDA](https://easyeda.com/) - Browser-based schematic capture and PCB layout platform.
- [Altium Designer](https://www.altium.com/altium-designer) - Professional PCB design environment for schematic, layout, routing, and manufacturing documentation.
- [OminiPCB PCB Design Guidelines](https://ominipcb.com/pcb-manufacturing/essential-pcb-design-guidelines-for-beginners-a-step-by-step-approach) - Practical checklist for stack-up, DFM rules, Gerber files, BOM, test access, and RFQ handoff.
- [OminiPCB Gerber Export Guide](https://ominipcb.com/pcb-manufacturing/how-do-i-generate-gerber-data-using-a-different-pcb-design-software) - Guide to preparing Gerber data from common PCB design tools before fabrication.

## PCB Calculators

- [OminiPCB Trace Width Calculator](https://ominipcb.com/engineering-tools/trace-width-calculator) - Estimate PCB trace width from current, copper thickness, layer location, temperature rise, and trace length.
- [OminiPCB Current Calculator](https://ominipcb.com/engineering-tools/current-calculator) - Estimate current capacity for an existing PCB trace.
- [OminiPCB Impedance Calculator](https://ominipcb.com/engineering-tools/impedance-calculator) - Estimate single-ended and differential impedance for microstrip and stripline geometries.
- [OminiPCB PCB Cost Estimator](https://ominipcb.com/engineering-tools/pcb-cost-estimator) - Estimate fabrication, assembly, component, testing, and lead-time cost drivers before RFQ.
- [OminiPCB PCB Stackup Calculator](https://ominipcb.com/engineering-tools/pcb-stackup-calculator) - Estimate layer count, board thickness, copper weight, dielectric spacing, and first-pass impedance widths.
- [OminiPCB Via Size Calculator](https://ominipcb.com/engineering-tools/via-size-calculator) - Estimate via current capacity, via count, annular ring, aspect ratio, resistance, and voltage drop.
- [OminiPCB PCB Weight Calculator](https://ominipcb.com/engineering-tools/pcb-weight-calculator) - Estimate bare PCB or assembled board weight from dimensions, material density, copper coverage, component mass, and quantity.
- [OminiPCB PCB Panelization Calculator](https://ominipcb.com/engineering-tools/pcb-panelization-calculator) - Estimate boards per panel, utilization, rail loss, rotation benefit, and panel count.
- [OminiPCB PCB Annular Ring Calculator](https://ominipcb.com/engineering-tools/pcb-annular-ring-calculator) - Calculate nominal and worst-case annular ring for vias and plated holes.
- [OminiPCB Creepage and Clearance Calculator](https://ominipcb.com/engineering-tools/pcb-creepage-clearance-calculator) - Screen high-voltage PCB spacing by voltage, pollution degree, material group, altitude, and insulation type.
- [OminiPCB Solder Paste Stencil Calculator](https://ominipcb.com/engineering-tools/solder-paste-stencil-calculator) - Calculate stencil aperture area ratio, aspect ratio, paste volume, and pad coverage.
- [OminiPCB BOM Attrition Calculator](https://ominipcb.com/engineering-tools/bom-attrition-calculator) - Estimate component overage, setup loss, attrition, package rounding, and extra component cost.
- [OminiPCB PCB Assembly Yield Calculator](https://ominipcb.com/engineering-tools/pcb-assembly-yield-calculator) - Estimate first-pass yield, expected failed boards, rework recovery, scrap, and escape risk.
- [Saturn PCB Toolkit](https://saturnpcb.com/saturn-pcb-toolkit/) - Desktop PCB calculator suite for trace, via, impedance, thermal, and manufacturing estimates.
- [KiCad PCB Calculator Documentation](https://docs.kicad.org/) - Documentation for KiCad's built-in engineering calculators.
- [DigiKey PCB Trace Width Calculator](https://www.digikey.com/en/resources/conversion-calculators/conversion-calculator-pcb-trace-width) - Web calculator for estimating PCB trace width from current and temperature-rise assumptions.

## Engineering Tools

- [OminiPCB PCB Engineering Tools](https://ominipcb.com/engineering-tools) - Index of PCB calculators for stack-up, trace width, via size, current capacity, impedance, cost, weight, panelization, stencil, BOM attrition, and assembly yield.
- [Gerbv](https://gerbv.github.io/) - Open-source Gerber file viewer.
- [KiBot](https://github.com/INTI-CMNB/KiBot) - Automation tool for KiCad outputs, fabrication packages, documentation, and CI workflows.
- [FreeRouting](https://github.com/freerouting/freerouting) - Open-source PCB autorouter.
- [openEMS](https://openems.de/) - Open-source electromagnetic field solver used for RF and high-speed simulation work.

## PCB Manufacturing

- [OminiPCB PCB Manufacturing](https://ominipcb.com/pcb-manufacturing) - PCB fabrication reference covering materials, stack-up, copper, controlled impedance, surface finish, panelization, and manufacturing review.
- [OminiPCB Controlled Impedance PCB Design Rules](https://ominipcb.com/pcb-manufacturing/controlled-impedance-pcb-design-rules) - Practical rules for trace geometry, stack-up control, materials, tolerances, coupons, and fabrication release.
- [OminiPCB HDI PCB Design Guide](https://ominipcb.com/pcb-manufacturing/hdi-pcb-design-comprehensive-guidelines-process-and-considerations) - HDI stack-up, microvia, via-in-pad, DFM, and manufacturing considerations.
- [OminiPCB PCB Via-in-Pad Design Rules](https://ominipcb.com/pcb-manufacturing/pcb-via-in-pad-design-rules) - Design guidance for BGA escape routing, filled and capped vias, solder wicking risk, and HDI boards.
- [OminiPCB FR4 vs Rogers PCB Material Guide](https://ominipcb.com/pcb-manufacturing/fr4-vs-rogers-pcb-material-which-one-should-i-choose-for-my-products) - Material comparison for cost, RF loss, thermal needs, and reliability.
- [OminiPCB ENIG PCB Surface Finish Guide](https://ominipcb.com/pcb-surface-finishes/enig-pcb-surface-finish) - Reference for ENIG finish advantages, limits, applications, and tradeoffs.
- [PCB Shopper](https://pcbshopper.com/) - PCB manufacturer price comparison service.
- [JLCPCB](https://jlcpcb.com/) - PCB fabrication and assembly service.
- [OSH Park](https://oshpark.com/) - PCB fabrication service focused on prototypes and small-batch boards.
- [Aisler](https://aisler.net/) - PCB manufacturing and assembly service based in Europe.
- [Elecrow](https://www.elecrow.com/) - PCB manufacturing and electronics prototyping service.
- [Seeed Fusion](https://www.seeedstudio.com/fusion_pcb.html) - PCB fabrication and assembly service from Seeed Studio.
- [PCBWay](https://www.pcbway.com/) - PCB fabrication and assembly service.
- [Eurocircuits](https://www.eurocircuits.com/) - European PCB prototype and small-series manufacturing service.

## PCB Assembly

- [OminiPCB PCB Assembly](https://ominipcb.com/pcb-assembly) - PCBA service reference covering SMT, THT, BGA, mixed assembly, BOM sourcing, DFM / DFA / DFT, AOI, X-Ray, ICT, and FCT.
- [OminiPCB Common SMT Assembly Challenges](https://ominipcb.com/pcba-assembly/common-challenges-in-smt-circuit-board-assembly-and-solutions) - Guide to stencil printing, placement, reflow, inspection, and SMT process controls.
- [OminiPCB BGA PCB Assembly Overview](https://ominipcb.com/pcba-assembly/demystifying-bga-pcbs-an-in-depth-overview) - Overview of BGA assembly risks, solder joints, pad design, and X-ray inspection.
- [OminiPCB AOI and X-Ray Inspection Planning](https://ominipcb.com/quality-reliability/how-to-plan-aoi-and-x-ray-inspection-for-high-reliability-pcb-assemblies) - Inspection planning guide for high-reliability PCB assemblies.
- [OminiPCB PCBA Quote Inspection and Test Scope](https://ominipcb.com/questions/what-smt-inspection-and-testing-should-a-pcba-quote-include) - Short reference for defining SPI, AOI, X-ray, ICT, programming, and FCT requirements in a PCBA quote.
- [JLCPCB PCB Assembly](https://jlcpcb.com/pcb-assembly) - PCB assembly service for prototype and production orders.
- [MacroFab](https://www.macrofab.com/) - Electronics manufacturing platform for PCB assembly and production management.
- [Screaming Circuits](https://www.screamingcircuits.com/) - Prototype and low-volume PCB assembly service.
- [PCBWay PCB Assembly](https://www.pcbway.com/pcb-assembly.html) - PCB assembly service for prototypes and small-batch production.
- [Elecrow PCB Assembly](https://www.elecrow.com/pcb-assembly.html) - PCB assembly service for prototype and turnkey builds.

## EMS and Electronics Manufacturing

- [OminiPCB EMS Services](https://ominipcb.com/ems-services) - EMS reference covering turnkey PCBA, SMT, THT, component sourcing, inspection, functional testing, box build, packaging, and delivery.
- [OminiPCB Electronics Manufacturing Process Guide](https://ominipcb.com/ems-solutions/electronics-manufacturing-process-a-comprehensive-guide) - Overview of EMS workflow from DFM to sourcing, assembly, testing, and release.
- [OminiPCB Electronics Product Development Guide](https://ominipcb.com/ems-solutions/electronics-product-development-from-idea-to-finished-device) - Guide to moving from product concept to assembled electronics.
- [OminiPCB PCB Programming Guide](https://ominipcb.com/ems-solutions/how-do-you-program-a-printed-circuit-board-step-by-step-guide) - Programming and production handoff guidance for assembled PCBs.
- [OminiPCB Box Build Assembly Guide](https://ominipcb.com/pcba-assembly/how-to-choose-a-suitable-box-build-assembly-manufacturer-for-your-device) - Guide to evaluating enclosure, cable, final assembly, test, and delivery scope.
- [IPC Connected Factory Exchange](https://www.ipc.org/ipc-cfx) - IPC standard for machine-to-machine communication in electronics manufacturing.
- [The Hermes Standard](https://www.the-hermes-standard.info/) - Open standard for board transfer and traceability communication in SMT lines.

## DFM / DFA / DFT

- [OminiPCB Capabilities](https://ominipcb.com/capabilities) - PCB, PCBA, EMS, SMT, THT, BGA, sourcing, test, and prototype-to-production capability overview.
- [OminiPCB Quality and Factory Evidence](https://ominipcb.com/quality) - Quality control reference covering factory evidence, DFM gates, sourcing checks, inspection scope, and documentation.
- [OminiPCB Rigid-Flex PCB DFM Tips](https://ominipcb.com/blog/dfm-tips-rigid-flex-pcb) - DFM guide for rigid-flex PCB manufacturing, bend radius, via placement, coverlay, and panelization risk.
- [OminiPCB Common DFM Issues](https://ominipcb.com/pcb-manufacturing/common-dfm-issues-and-how-to-avoid-them-in-pcb-design) - Guide to trace, drill, annular ring, stack-up, surface finish, and documentation issues that delay PCB manufacturing.
- [OminiPCB SMT Stencil and Paste Printing Risk](https://ominipcb.com/pcba-assembly/how-to-evaluate-smt-stencil-and-solder-paste-printing-risk-before) - Checklist for stencil aperture design, solder paste printing, and inspection coverage before PCBA.
- [Eurocircuits PCB Design Guidelines](https://www.eurocircuits.com/pcb-design-guidelines/) - PCB design-for-manufacturing guidance from a European PCB manufacturer.
- [IPC Standards](https://www.ipc.org/ipc-standards) - Standards used across PCB design, fabrication, assembly, inspection, and electronics manufacturing.

## Component Sourcing

- [OminiPCB BOM to PCBA Quote](https://ominipcb.com/bom-quote) - Browser-assisted BOM parsing and component cost estimation workflow before engineering RFQ review.
- [OminiPCB BOM Risk Strategy for Turnkey PCB Assembly](https://ominipcb.com/blog/global-chip-shortage-strategies) - Guide to AVL planning, lifecycle review, substitute approval, and component risk control.
- [OminiPCB SMT Assembly Quote File Checklist](https://ominipcb.com/questions/what-files-are-needed-for-smt-assembly-quote) - Reference for Gerber, BOM, centroid, drawings, revision, sourcing rules, inspection, programming, and test files.
- [DigiKey](https://www.digikey.com/) - Global electronic component distributor and part search platform.
- [Mouser Electronics](https://www.mouser.com/) - Global distributor of semiconductors, passives, connectors, electromechanical parts, and development tools.
- [LCSC](https://www.lcsc.com/) - Electronic component distributor with strong coverage of Asia-sourced parts.
- [Octopart](https://octopart.com/) - Electronic component search engine for distributor availability, pricing, lifecycle data, and datasheets.
- [SnapEDA](https://www.snapeda.com/) - Electronic CAD model library for symbols, footprints, and 3D models.

## Knowledge and Learning

- [OminiPCB Blog](https://ominipcb.com/blog) - PCB manufacturing, PCB assembly, EMS, DFM, component sourcing, quality testing, and PCB design knowledge hub.
- [OminiPCB PCB Today](https://ominipcb.com/pcb-today) - PCB and PCBA industry intelligence covering technology, supply chain, manufacturing, and market developments.
- [OminiPCB ENIG vs HASL PCB Surface Finish](https://ominipcb.com/comparisons/enig-vs-hasl) - Comparison of ENIG and HASL surface finishes for solderability, flatness, shelf life, and cost.
- [OminiPCB FR4 vs Rogers 4350B PCB Material](https://ominipcb.com/comparisons/fr4-vs-rogers-4350b) - Comparison of FR-4 and Rogers 4350B for RF loss, dielectric control, impedance, and cost.
- [OminiPCB AOI vs X-Ray PCB Assembly Inspection](https://ominipcb.com/comparisons/aoi-vs-x-ray-inspection) - Comparison of optical and X-ray inspection use cases in PCB assembly.
- [SparkFun Tutorials](https://www.sparkfun.com/tutorials) - Electronics tutorials covering circuits, components, tools, soldering, and embedded hardware.
- [Adafruit Learning System](https://learn.adafruit.com/) - Practical electronics, microcontroller, and hardware project tutorials.
- [All About Circuits](https://www.allaboutcircuits.com/) - Electronics engineering articles, textbooks, technical references, and forums.
- [Electronics Stack Exchange](https://electronics.stackexchange.com/) - Q&A community for electronics design, circuits, PCB layout, and debugging.
- [EEVblog Forum](https://www.eevblog.com/forum/) - Electronics engineering discussion forum with hardware design, test, repair, and manufacturing topics.

## Industry Resources

- [Awesome Electronics](https://github.com/kitspace/awesome-electronics) - Curated electronics resources for engineers and hardware developers.
- [Awesome PCB](https://github.com/Mindar/awesome-pcb) - Curated PCB design and electronics resources.
- [Awesome Hardware Production](https://github.com/anujdeshpande/awesome-hardware-production) - Resources for taking hardware products from design to production.
- [IPC](https://www.ipc.org/) - Electronics manufacturing industry association and standards organization.
- [IEEE](https://www.ieee.org/) - Professional association for electrical, electronics, and computing engineering.
- [IEEE Xplore](https://ieeexplore.ieee.org/) - Research database for engineering papers, conference proceedings, and technical standards.
- [Open Source Hardware Association](https://www.oshwa.org/) - Organization supporting open-source hardware practices and certification.

## Contributing

Contributions are welcome.

Please submit resources that are useful to PCB designers, electronics engineers, hardware developers, manufacturers, and researchers.

When adding a resource:

- Prefer technically useful and actively maintained resources.
- Use a direct link to the relevant resource.
- Avoid promotional or affiliate-only pages.
- Keep descriptions concise and factual.
- Check for existing entries before submitting a duplicate.
- Do not submit low-quality SEO pages.

## License

This list is dedicated to the public domain under the [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) license.
