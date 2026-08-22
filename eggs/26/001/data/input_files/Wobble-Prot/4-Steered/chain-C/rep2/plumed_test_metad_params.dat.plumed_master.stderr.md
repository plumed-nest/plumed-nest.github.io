**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-C/rep2/plumed_test_metad_params.dat   
Download: [zipped raw stdout](plumed_test_metad_params.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_test_metad_params.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Deprot/chain-C/01_box-min/ref.pdb
[runnervm76f27:04548] *** Process received signal ***
[runnervm76f27:04548] Signal: Aborted (6)
[runnervm76f27:04548] Signal code:  (-6)
[runnervm76f27:04548] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb15e245330]
[runnervm76f27:04548] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb15e29ec0c]
[runnervm76f27:04548] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb15e24527e]
[runnervm76f27:04548] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb15e2288ff]
[runnervm76f27:04548] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb15e6a5ff5]
[runnervm76f27:04548] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb15e6bb0da]
[runnervm76f27:04548] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb15e6a5a55]
[runnervm76f27:04548] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb15e6a5a6f]
[runnervm76f27:04548] [ 8] plumed_master(+0x146dd)[0x559c023706dd]
[runnervm76f27:04548] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb15e22a1ca]
[runnervm76f27:04548] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb15e22a28b]
[runnervm76f27:04548] [11] plumed_master(+0x15365)[0x559c02371365]
[runnervm76f27:04548] *** End of error message ***
</pre>
{% endraw %}
