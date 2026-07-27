**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-C/rep2/plumed_test_metad_params.dat   
Download: [zipped raw stdout](plumed_test_metad_params.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_test_metad_params.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Deprot/chain-C/01_box-min/ref.pdb
[runnervmvrwv9:04959] *** Process received signal ***
[runnervmvrwv9:04959] Signal: Aborted (6)
[runnervmvrwv9:04959] Signal code:  (-6)
[runnervmvrwv9:04959] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f67dba45330]
[runnervmvrwv9:04959] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f67dba9eb2c]
[runnervmvrwv9:04959] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f67dba4527e]
[runnervmvrwv9:04959] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f67dba288ff]
[runnervmvrwv9:04959] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f67dbea5ff5]
[runnervmvrwv9:04959] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f67dbebb0da]
[runnervmvrwv9:04959] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f67dbea5a55]
[runnervmvrwv9:04959] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f67dbea5a6f]
[runnervmvrwv9:04959] [ 8] plumed_master(+0x146dd)[0x55ebdc2ce6dd]
[runnervmvrwv9:04959] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f67dba2a1ca]
[runnervmvrwv9:04959] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f67dba2a28b]
[runnervmvrwv9:04959] [11] plumed_master(+0x15365)[0x55ebdc2cf365]
[runnervmvrwv9:04959] *** End of error message ***
</pre>
{% endraw %}
