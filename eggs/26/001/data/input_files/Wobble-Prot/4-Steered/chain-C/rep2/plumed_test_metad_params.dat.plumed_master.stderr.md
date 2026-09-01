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
[runnervmgx7h7:04158] *** Process received signal ***
[runnervmgx7h7:04158] Signal: Aborted (6)
[runnervmgx7h7:04158] Signal code:  (-6)
[runnervmgx7h7:04158] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f83ada45330]
[runnervmgx7h7:04158] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f83ada9ec0c]
[runnervmgx7h7:04158] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f83ada4527e]
[runnervmgx7h7:04158] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f83ada288ff]
[runnervmgx7h7:04158] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f83adea5ff5]
[runnervmgx7h7:04158] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f83adebb0da]
[runnervmgx7h7:04158] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f83adea5a55]
[runnervmgx7h7:04158] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f83adea5a6f]
[runnervmgx7h7:04158] [ 8] plumed_master(+0x146dd)[0x5574ede686dd]
[runnervmgx7h7:04158] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f83ada2a1ca]
[runnervmgx7h7:04158] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f83ada2a28b]
[runnervmgx7h7:04158] [11] plumed_master(+0x15365)[0x5574ede69365]
[runnervmgx7h7:04158] *** End of error message ***
</pre>
{% endraw %}
