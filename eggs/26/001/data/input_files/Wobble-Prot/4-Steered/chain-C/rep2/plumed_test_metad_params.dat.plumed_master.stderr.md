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
[runnervmmklqx:04396] *** Process received signal ***
[runnervmmklqx:04396] Signal: Aborted (6)
[runnervmmklqx:04396] Signal code:  (-6)
[runnervmmklqx:04396] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7235c45330]
[runnervmmklqx:04396] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7235c9eb2c]
[runnervmmklqx:04396] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7235c4527e]
[runnervmmklqx:04396] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7235c288ff]
[runnervmmklqx:04396] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f72360a5ff5]
[runnervmmklqx:04396] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f72360bb0da]
[runnervmmklqx:04396] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f72360a5a55]
[runnervmmklqx:04396] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f72360a5a6f]
[runnervmmklqx:04396] [ 8] plumed_master(+0x146dd)[0x556ab404a6dd]
[runnervmmklqx:04396] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7235c2a1ca]
[runnervmmklqx:04396] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7235c2a28b]
[runnervmmklqx:04396] [11] plumed_master(+0x15365)[0x556ab404b365]
[runnervmmklqx:04396] *** End of error message ***
</pre>
{% endraw %}
