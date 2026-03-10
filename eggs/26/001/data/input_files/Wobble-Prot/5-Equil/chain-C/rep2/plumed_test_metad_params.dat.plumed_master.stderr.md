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
[runnervm0kj6c:04813] *** Process received signal ***
[runnervm0kj6c:04813] Signal: Aborted (6)
[runnervm0kj6c:04813] Signal code:  (-6)
[runnervm0kj6c:04813] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc0b0245330]
[runnervm0kj6c:04813] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc0b029eb2c]
[runnervm0kj6c:04813] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc0b024527e]
[runnervm0kj6c:04813] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc0b02288ff]
[runnervm0kj6c:04813] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc0b06a5ff5]
[runnervm0kj6c:04813] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc0b06bb0da]
[runnervm0kj6c:04813] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc0b06a5a55]
[runnervm0kj6c:04813] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc0b06a5a6f]
[runnervm0kj6c:04813] [ 8] plumed_master(+0x146dd)[0x55c4fef246dd]
[runnervm0kj6c:04813] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc0b022a1ca]
[runnervm0kj6c:04813] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc0b022a28b]
[runnervm0kj6c:04813] [11] plumed_master(+0x15365)[0x55c4fef25365]
[runnervm0kj6c:04813] *** End of error message ***
</pre>
{% endraw %}
