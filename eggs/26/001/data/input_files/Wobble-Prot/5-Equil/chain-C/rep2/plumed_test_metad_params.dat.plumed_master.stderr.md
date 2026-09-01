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
[runnervmgx7h7:04622] *** Process received signal ***
[runnervmgx7h7:04622] Signal: Aborted (6)
[runnervmgx7h7:04622] Signal code:  (-6)
[runnervmgx7h7:04622] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8226045330]
[runnervmgx7h7:04622] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f822609ec0c]
[runnervmgx7h7:04622] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f822604527e]
[runnervmgx7h7:04622] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f82260288ff]
[runnervmgx7h7:04622] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f82264a5ff5]
[runnervmgx7h7:04622] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f82264bb0da]
[runnervmgx7h7:04622] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f82264a5a55]
[runnervmgx7h7:04622] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f82264a5a6f]
[runnervmgx7h7:04622] [ 8] plumed_master(+0x146dd)[0x5572b41266dd]
[runnervmgx7h7:04622] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f822602a1ca]
[runnervmgx7h7:04622] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f822602a28b]
[runnervmgx7h7:04622] [11] plumed_master(+0x15365)[0x5572b4127365]
[runnervmgx7h7:04622] *** End of error message ***
</pre>
{% endraw %}
