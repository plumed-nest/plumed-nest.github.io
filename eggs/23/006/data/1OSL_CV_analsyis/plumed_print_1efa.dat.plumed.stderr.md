**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  1OSL_CV_analsyis/plumed_print_1efa.dat   
Download: [zipped raw stdout](plumed_print_1efa.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_print_1efa.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1efa_noTet_99sbws_proc_mod_resID.pdb
[runnervm76f27:07056] *** Process received signal ***
[runnervm76f27:07056] Signal: Aborted (6)
[runnervm76f27:07056] Signal code:  (-6)
[runnervm76f27:07056] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f79d6645330]
[runnervm76f27:07056] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f79d669ec0c]
[runnervm76f27:07056] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f79d664527e]
[runnervm76f27:07056] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f79d66288ff]
[runnervm76f27:07056] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f79d6aa5ff5]
[runnervm76f27:07056] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f79d6abb0da]
[runnervm76f27:07056] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f79d6aa5a55]
[runnervm76f27:07056] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f79d6aa5a6f]
[runnervm76f27:07056] [ 8] plumed(+0x146dd)[0x559e1009c6dd]
[runnervm76f27:07056] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f79d662a1ca]
[runnervm76f27:07056] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f79d662a28b]
[runnervm76f27:07056] [11] plumed(+0x15365)[0x559e1009d365]
[runnervm76f27:07056] *** End of error message ***
</pre>
{% endraw %}
