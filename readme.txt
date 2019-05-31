This is the readme for the model associated with the paper:

Ovsepian SV, Steuber V, Le Berre M, O'Hara L, O'Leary VB, Dolly JO
(2013) A defined heteromeric KV1 channel stabilizes the intrinsic
pacemaking and regulates the output of deep cerebellar nuclear neurons
to thalamic targets. J Physiol 591:1771-91

This model was contributed by Dr Volker Steuber.  The computer code
was written in NEURON which is freely available at
http://www.neuron.yale.edu

Use: auto-launch from ModelDB or download, extract, and compile the
mod files with the "nrnivmodl" command after cd'ing to the extracted
folder (linux/unix), or drag and drop the folder on the mknrndll icon
(Mac OS X), or cd'ing to the folder with mknrndll (mswin). Start the
simulation by pressing return a couple times (during autolaunch to
compile and start), drag and drop one of the below files on the nrngui
icon (Mac OS X), or double clicking one of the below files (mswin).

The following scripts replicate figures in Ovsepian et al. (2013)

Fig 9A,B: DCN_spontact_loop_main.hoc
Fig 9C,D: DCN_rebound_main.hoc
Fig 9E: DCN_cip_fi_main.hoc
Fig 9F: DCN_cip_axis_main.hoc

They each produce the appropriate data files and then exit.  Note that
DCN_cip_axis_main.hoc takes just a few minutes so if you want a quick
demo try that instead of the longer scripts.
