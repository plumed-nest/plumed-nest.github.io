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
[runnervm0kj6c:04346] *** Process received signal ***
[runnervm0kj6c:04346] Signal: Aborted (6)
[runnervm0kj6c:04346] Signal code:  (-6)
[runnervm0kj6c:04346] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb2c3645330]
[runnervm0kj6c:04346] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb2c369eb2c]
[runnervm0kj6c:04346] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb2c364527e]
[runnervm0kj6c:04346] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb2c36288ff]
[runnervm0kj6c:04346] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb2c3aa5ff5]
[runnervm0kj6c:04346] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb2c3abb0da]
[runnervm0kj6c:04346] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb2c3aa5a55]
[runnervm0kj6c:04346] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb2c3aa5a6f]
[runnervm0kj6c:04346] [ 8] plumed_master(+0x146dd)[0x5555926186dd]
[runnervm0kj6c:04346] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb2c362a1ca]
[runnervm0kj6c:04346] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb2c362a28b]
[runnervm0kj6c:04346] [11] plumed_master(+0x15365)[0x555592619365]
[runnervm0kj6c:04346] *** End of error message ***
</pre>
{% endraw %}
