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
[runnervmmklqx:04867] *** Process received signal ***
[runnervmmklqx:04867] Signal: Aborted (6)
[runnervmmklqx:04867] Signal code:  (-6)
[runnervmmklqx:04867] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9d67a45330]
[runnervmmklqx:04867] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9d67a9eb2c]
[runnervmmklqx:04867] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9d67a4527e]
[runnervmmklqx:04867] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9d67a288ff]
[runnervmmklqx:04867] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9d67ea5ff5]
[runnervmmklqx:04867] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9d67ebb0da]
[runnervmmklqx:04867] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9d67ea5a55]
[runnervmmklqx:04867] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9d67ea5a6f]
[runnervmmklqx:04867] [ 8] plumed_master(+0x146dd)[0x557aff1656dd]
[runnervmmklqx:04867] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9d67a2a1ca]
[runnervmmklqx:04867] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9d67a2a28b]
[runnervmmklqx:04867] [11] plumed_master(+0x15365)[0x557aff166365]
[runnervmmklqx:04867] *** End of error message ***
</pre>
{% endraw %}
