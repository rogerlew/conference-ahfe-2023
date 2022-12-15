# conference-ahfe-2023

https://ahfe.org

AHFE 2023 International Conference

July 20-24, 2023 - San Francisco, California, USA


## Abstract

### Human error and performance modeling with virtual operator model (HUNTER) tightly coupled to Rancor Microworld Nuclear Power Plant Simulator

Light water reactors in the United States produce low-carbon baseload electricity and account for roughly 20% of generation. Continued operation is critical to a low-carbon energy resilient future, and human operators are essential to the operation of these plants. To date, the US nuclear power industry has an impeccable track record of safety. Many of these plants are planning on operating for an additional 20 or more years. Modeling and quantifying the role of human perception, cognition, and decision-making and their impacts on plant safety is critical to the continued operation of these plants.

The Human Unimodel for Nuclear Technology to Enhance Reliability (HUNTER) framework was initially conceived in 2016 (Boring et al., 2016) as the offshoot of dynamic risk modeling work to support severe accident scenarios like flooding. Unlike traditional (static) risk modeling HUNTER has a dynamic version of SPAR-H to calculate performance shaping factors (PSFs) based on evolving plant conditions. HUNTER also models task level Goals-Operators-Methods-Selection rules (GOMS)-HRA as the operator walks through procedure steps. Here we describe how the HUNTER virtual operator model was tightly coupled with the Rancor Nuclear Power Plant Microworld as part of a suite of probabilistic risk assessment (PRA) tools being developed under the Risk-Informed Safety Margin Characterization (RISMC; now Risk-Informed Systems Analysis or RISA) Pathway under the U.S. Department of Energy’s Light Water Reactor Sustainability (LWRS) Program. 

Rancor was developed to address challenges facing human factors and human reliability analysis researchers investigating human performance in nuclear process control settings. Rancor is a simplified nuclear process control simulator developed to support human factors and human reliability analysis (Ulrich, 2017). Nuclear process control simulators have existed for decades, starting when nuclear utilities developed and deployed mimics of their actual nuclear power plant main control rooms to support operator licensing and training (Boring, 2011). The requirements for these simulators followed high-profile nuclear incidents, with a goal to ensure reactor operators could safely respond to upset conditions at their plants. Unfortunately, utilizing these simulators requires a great deal of plant specific expertise and obtaining data for research purposes is not possible. As such, Rancor is well suited as a testbed to develop a tightly integrated HUNTER/simulator model. Rancor has a growing corpus of operations data from student and professional operators. 

Here we modeled two scenarios (startup and loss of feedwater) and demonstrated that the virtual operator can complete task evolutions. This represents a significant and successful demonstration for coupling a virtual operator with a virtual plant model to support dynamic HRA. We found that the HUNTER model closely matched the timing data for the normal startup procedure, but overestimated task completion times for the abnormal loss of feedwater scenario. The HEPs were found to be an order of magnitude lower than human operators. Future work will calibrate HUNTER/Rancor for dynamic human reliability analysis. 
