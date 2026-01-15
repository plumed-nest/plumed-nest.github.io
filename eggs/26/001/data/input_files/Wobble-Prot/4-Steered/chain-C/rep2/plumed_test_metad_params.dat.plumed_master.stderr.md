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
[runnervmi13qx:31815] *** Process received signal ***
[runnervmi13qx:31815] Signal: Aborted (6)
[runnervmi13qx:31815] Signal code:  (-6)
[runnervmi13qx:31815] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3a82445330]
[runnervmi13qx:31815] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3a8249eb2c]
[runnervmi13qx:31815] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3a8244527e]
[runnervmi13qx:31815] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3a824288ff]
[runnervmi13qx:31815] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3a828a5ff5]
[runnervmi13qx:31815] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3a828bb0da]
[runnervmi13qx:31815] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3a828a5a55]
[runnervmi13qx:31815] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3a828a5a6f]
[runnervmi13qx:31815] [ 8] plumed_master(+0x146dd)[0x55a7640586dd]
[runnervmi13qx:31815] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3a8242a1ca]
[runnervmi13qx:31815] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3a8242a28b]
[runnervmi13qx:31815] [11] plumed_master(+0x15365)[0x55a764059365]
[runnervmi13qx:31815] *** End of error message ***
</pre>
{% endraw %}
