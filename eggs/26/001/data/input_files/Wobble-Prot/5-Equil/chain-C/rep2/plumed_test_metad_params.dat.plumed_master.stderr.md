**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-C/rep2/plumed_test_metad_params.dat   
Download: [zipped raw stdout](plumed_test_metad_params.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_test_metad_params.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Deprot/chain-C/01_box-min/ref.pdb
[runnervmkj6or:04763] *** Process received signal ***
[runnervmkj6or:04763] Signal: Aborted (6)
[runnervmkj6or:04763] Signal code:  (-6)
[runnervmkj6or:04763] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbdfca45330]
[runnervmkj6or:04763] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbdfca9eb2c]
[runnervmkj6or:04763] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbdfca4527e]
[runnervmkj6or:04763] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbdfca288ff]
[runnervmkj6or:04763] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbdfcea5ff5]
[runnervmkj6or:04763] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbdfcebb0da]
[runnervmkj6or:04763] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbdfcea5a55]
[runnervmkj6or:04763] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbdfcea5a6f]
[runnervmkj6or:04763] [ 8] plumed_master(+0x146dd)[0x5641b47d06dd]
[runnervmkj6or:04763] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbdfca2a1ca]
[runnervmkj6or:04763] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbdfca2a28b]
[runnervmkj6or:04763] [11] plumed_master(+0x15365)[0x5641b47d1365]
[runnervmkj6or:04763] *** End of error message ***
</pre>
{% endraw %}
