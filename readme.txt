This is the readme.txt for a pyramidal cell model from the paper:

Durstewitz D, Seamans JK, Sejnowski TJ (2000) Dopamine-mediated
stabilization of delay-period activity in a network model of
prefrontal cortex. J Neurophysiol 83:1733-50

Abstract:

The prefrontal cortex (PFC) is critically involved in working memory,
which underlies memory-guided, goal-directed behavior. During
working-memory tasks, PFC neurons exhibit sustained elevated activity,
which may reflect the active holding of goal-related information or
the preparation of forthcoming actions. Dopamine via the D1 receptor
strongly modulates both this sustained (delay-period) activity and
behavioral performance in working-memory tasks. However, the function
of dopamine during delay-period activity and the underlying neural
mechanisms are only poorly understood. Recently we proposed that
dopamine might stabilize active neural representations in PFC circuits
during tasks involving working memory and render them robust against
interfering stimuli and noise. To further test this idea and to
examine the dopamine-modulated ionic currents that could give rise to
increased stability of neural representations, we developed a network
model of the PFC consisting of multicompartment neurons equipped with
Hodgkin-Huxley-like channel kinetics that could reproduce in vitro
whole cell and in vivo recordings from PFC neurons. Dopaminergic
effects on intrinsic ionic and synaptic conductances were implemented
in the model based on in vitro data. Simulated dopamine strongly
enhanced high, delay-type activity but not low, spontaneous activity
in the model network. Furthermore the strength of an afferent
stimulation needed to disrupt delay-type activity increased with the
magnitude of the dopamine-induced shifts in network parameters, making
the currently active representation much more stable. Stability could
be increased by dopamine-induced enhancements of the persistent Na(+)
and N-methyl-D-aspartate (NMDA) conductances. Stability also was
enhanced by a reduction in AMPA conductances. The increase in GABA(A)
conductances that occurs after stimulation of dopaminergic D1
receptors was necessary in this context to prevent uncontrolled,
spontaneous switches into high-activity states (i.e., spontaneous
activation of task-irrelevant representations). In conclusion, the
dopamine-induced changes in the biophysical properties of intrinsic
ionic and synaptic conductances conjointly acted to highly increase
stability of activated representations in PFC networks and at the same
time retain control over network behavior and thus preserve its
ability to adequately respond to task-related stimuli. Predictions of
the model can be tested in vivo by locally applying specific D1
receptor, NMDA, or GABA(A) antagonists while recording from PFC
neurons in delayed reaction-type tasks with interfering stimuli.

Model usage:

Download and expand the archive.  Compile the mod files with mknrndll
(windows), drag and drop the pcell folder onto the mknrndll icon
(mac), or run nrnuvmodl in the pcell directory (unix).  Then start the
program by double clicking the mosinit.hoc file (windows), drag the
mosinit.hoc file to the nrngui icon (mac), or type "nrngui
mosinit.hoc" in the pcell directory (unix).

When the model starts press the button to create the right hand column
of figure 2.

For questions or comments please contact:
Dr Daniel Durstewitz
Centre for Theoretical and Computational Neuroscience
University of Plymouth
Portland Square, A 220
Plymouth, PL4 8AA, UK
daniel.durstewitz@plymouth.ac.uk

The model files are also available at the web site:
http://www.pion.ac.uk/~daniel/
