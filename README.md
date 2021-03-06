# ioniq 42
tldr: Upgrade the 28kWh 2017 ioniq EV so that it gets 42kWh

The 2017 ioniq EV has a 28kWh 96S2P LG LQ 1729-A2 with a weight of around 260 kg. The plan is to buy another complete battery, put it into the trunk, and link it to the main battery power cord so that the car will experience a larger capacity. Because the battery is 2P (meaning 2-parallel) it is only possible to add either 14kWh or 28kWH. In order to achieve a good tradeoff between weight and range, I will go for +14 kWh, summing up to 42kWh(!). The original car has a summer/winter range of about 200/170 km, and I hope I can achieve somewhere about 300/260. Another perk of this battery expansion is that the main battery will need less cycles for the same amount of trips, which means that the battery health will be prolonged significantly.

In this log I will reverse engineer and explain how I hopefully succeed to fit this extra battery capacity.


## Phase 1: Validate concept

The main idea is to link the aux (short for auxiliary) battery with a parallel connection directly onto the main battery cord that connects to the hood junction box. I need the aux battery to be linked in parallel with the main battery in 3 use states: 1) driving, 2) OBC charging and 3) DC charging


In short:
  - [x] Buy an used EV HV cord
  - [x] Before I start modifying the used EV HV cord, I should probably check whether it is possible to order the opposing plugs online. This will make it possible to put a spacer cord between the EV HV cord end plug and the hood junction box, easily providing parallel access to the main battery: Doesn't seem to be possible.

#### Test voltage on evhv line
- [ ] Make a test-mod evhv line 
- [ ] Before mounting on car, test that the polarity is the same as the original cable.
- [ ] Connect a thin wire from which I can check that the battery is connected in all three use states.
- [ ] Check that the test-modified


  - [ ] Make a modified EV HV cord and put it into the car



## Phase 2: Dummy battery

Buy and build a very small battery, possibly a 96S1P battery without a BMS which I can connect to


In short:
  - [ ] Connect a heavy gauge wire that is able to handle full current. The EPCU is able to demand 248A at peak acceleration (88kW), and since the aux battery will have a capacity half of the main battery, the heavy gauge aux wire should be able to withstand one third which is about 82A. 
  - [ ] Run this wire to the trunk of the car.

## Phase 3: Buy a salvaged ioniq 2017-2019 28kWh battery


  - [ ] Disassemble individual cells


## Phase 4: Reconfigure the salvaged battery into a 14kWh trunk application

  - [ ] Build a sheet metal-rivets assembled fireproof box and throw in the 96 cells.

## Phase 4: BMS (Battery Management System)


## Phase 5: Build a case around the integrated aux battery and put it into the trunk.


## Phase ?: Cooling the battery on long trips

## Phase ?: Heating the battery in Norwegian winter temperatures


