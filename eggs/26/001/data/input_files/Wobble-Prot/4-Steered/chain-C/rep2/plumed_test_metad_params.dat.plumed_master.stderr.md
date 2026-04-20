**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-C/rep2/plumed_test_metad_params.dat   
Download: [zipped raw stdout](plumed_test_metad_params.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_test_metad_params.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Deprot/chain-C/01_box-min/ref.pdb
[runnervmeorf1:04579] *** Process received signal ***
[runnervmeorf1:04579] Signal: Aborted (6)
[runnervmeorf1:04579] Signal code:  (-6)
[runnervmeorf1:04579] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe246645330]
[runnervmeorf1:04579] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe24669eb2c]
[runnervmeorf1:04579] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe24664527e]
[runnervmeorf1:04579] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe2466288ff]
[runnervmeorf1:04579] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe246aa5ff5]
[runnervmeorf1:04579] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe246abb0da]
[runnervmeorf1:04579] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe246aa5a55]
[runnervmeorf1:04579] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe246aa5a6f]
[runnervmeorf1:04579] [ 8] plumed_master(+0x146dd)[0x55db6861f6dd]
[runnervmeorf1:04579] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe24662a1ca]
[runnervmeorf1:04579] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe24662a28b]
[runnervmeorf1:04579] [11] plumed_master(+0x15365)[0x55db68620365]
[runnervmeorf1:04579] *** End of error message ***
</pre>
{% endraw %}
