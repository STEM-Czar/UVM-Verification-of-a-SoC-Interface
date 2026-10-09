# UVM-Verification-of-a-SoC-Interface
The objective is to develop a reusable UVM verification environment for a transaction based interface representative of verification work performed on modern SoC IP.


### Phase 1 | Fundamentals and DUT Design
- [ ] Learn the basic UVM architecture: sequence item, sequence, sequencer, driver, monitor, agent, scoreboard, environment, and test.
- [ ] Learn how transaction based verification differs from directed RTL testbenches.

### Phase 2 | DUT Design
- [ ] Create a simple 32-bit register controlled peripheral DUT.
- [ ] Design the DUT with address, write data, read data, read/write control, reset, and error signals.
- [ ] Create a small register map with control, status, and read only registers.
- [ ] Design the DUT to reject invalid register addresses.

### Phase 3 | UVM Transaction Infrastructure
- [ ] Create the UVM sequence item to represent a register transaction.
- [ ] Create randomized read and write transactions.
- [ ] Create the UVM sequencer to provide transactions to the driver.
- [ ] Create the UVM driver to convert transactions into DUT interface activity.
- [ ] Create the UVM monitor to observe transactions from the DUT interface.
- [ ] Create the UVM agent to contain the sequencer, driver, and monitor.

### Phase 4 | Checking and Environment Integration
- [ ] Create the scoreboard to compare expected and actual register behavior.
- [ ] Create the UVM environment to connect the agent and scoreboard.

### Phase 5 | Test Scenarios and Stimulus
- [ ] Create sequences for register reads, register writes, invalid accesses, and reset scenarios.
- [ ] Add constrained random stimulus for addresses, operations, and data.

### Phase 6 | Assertions and Functional Coverage
- [ ] Add assertions for basic interface and register behavior.
- [ ] Add functional coverage for operations, addresses, valid and invalid accesses, reset, and errors.
- [ ] Add cross coverage between read/write operations and register addresses.

### Phase 7 | Simulation and Debugging
- [ ] Run the complete UVM testbench and debug failures using logs and waveforms.
- [ ] Generate a coverage report and identify untested scenarios.

### Phase 8 | Documentation and Final Deliverables
- [ ] Document the UVM architecture, verification results, coverage, and remaining limitations.
