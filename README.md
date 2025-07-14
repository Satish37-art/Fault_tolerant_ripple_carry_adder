# Fault_tolerant_ripple_carry_adder
Fault tolerant ripple carry adder comes under when uses for critical applications like aviation,space,medical industry etc.
There are so many techniques to design a fault tolerant ripple carry adder as TMR,DMR but we have used the dynamic redundancy technique using mux.
We design it with built_in_self_test for automatic testing.
We have used some c_testable conectp so the cost of testing should not go beyound minimal.For c_testable we first make the design regular so that the number of inputs of bits increses the test patterns are still constant
In this Project there are basically three modules i. Fault_tolerant_ripple_carry_adder ii.Test Patteren generator circuit iii.Mux selection line circuit.
The whole design working on two modes i. Normal mode(data mode) T=0 ii. Test mode(fault detection mode) t=1.
If there is any fault during testing mode then the mux selection line fixes to 1 for the MSB side.
