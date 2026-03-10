**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-C/rep2/plumed_test_metad_params.dat   
Download: [zipped raw stdout](plumed_test_metad_params.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_test_metad_params.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Deprot/chain-C/01_box-min/ref.pdb
[runnervm0kj6c:04330] *** Process received signal ***
[runnervm0kj6c:04330] Signal: Aborted (6)
[runnervm0kj6c:04330] Signal code:  (-6)
[runnervm0kj6c:04330] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f12be045330]
[runnervm0kj6c:04330] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f12be09eb2c]
[runnervm0kj6c:04330] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f12be04527e]
[runnervm0kj6c:04330] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f12be0288ff]
[runnervm0kj6c:04330] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f12be4a5ff5]
[runnervm0kj6c:04330] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f12be4bb0da]
[runnervm0kj6c:04330] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f12be4a5a55]
[runnervm0kj6c:04330] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f12be4a5a6f]
[runnervm0kj6c:04330] [ 8] plumed(+0x146dd)[0x55c39c8456dd]
[runnervm0kj6c:04330] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f12be02a1ca]
[runnervm0kj6c:04330] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f12be02a28b]
[runnervm0kj6c:04330] [11] plumed(+0x15365)[0x55c39c846365]
[runnervm0kj6c:04330] *** End of error message ***
</pre>
{% endraw %}
