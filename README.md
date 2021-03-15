# Node01
Node01 is wireless mesh node. This node is the basis of backbone network.

###  Progress checklist
**Documentation**
- [ ] Technical specifications added. (4h)
- [ ] Description. (1h)
- [ ] Hardware. (1h)
- [ ] Source. (0h)

**Hardware**
- [ ] Schematics designed. (1h)
- [ ] Simulations. (0h)
- [ ] PCB routed. (0h)
- [ ] Simulations. (0h)
- [ ] Rev. 1 manufactured. (0h)
- [ ] Rev. 1 tested. (0h)
- [ ] Changes to Rev. 1 made. (0h)
- [ ] Rev. 2 manufactured. (0h)
- [ ] Rev. 2 tested. (0h)
- [ ] Test passed. (0h)


**Software**
- [ ] Coding style guidleines added. (0h)
- [ ] Project guidlines added. (0h)
- [ ] Project organized. (0h)
- [ ] Build system created. (0h)
- [ ] Unit test system created. (0h)
- [ ] ... TBA
- [ ] MVP. (0h)
- [ ] Release of v.1.0.0. (0h)

### Requirements
**Hardware**
* Based on Nordic Semiconductor IC (ex. nRF52840, ...)
* Continuous RF operation RX/TX
* Mostly static geo-position
* Autonomous power supply with a backup battery source
* Energy storage is supercap or LiFePO4(operates at low temperatures)
* Power connector for external solar panel or another energy source if available
* RF front end - range extender, switchable
* Switchable antenna to on-board or external SMA connector
* -40...+80 C deg outdoor temperature of operation
* minimum IP-63 protection
* Self monitor feature (integral temperature, battery lifetime monitoring)
* Flash storage IC
*

**Software**
* Proprietary 2.4GHz protocol
* Operates as a router/switch
* Event based cooperative scheduler(in plans)
* Event-driven active object paradigm
* Or some of RTOS
* Modular hardware dependant part i.e. change in base board does not change logic
of operation. Hardware are accessed throught API.
* C++ mixed with C and ASM for performance critical code sections(if possible)
* FOTA update
* Communication security: TBD !
* Minimal maintenance concept
* Self test feature
* Delay reliable communication
*
