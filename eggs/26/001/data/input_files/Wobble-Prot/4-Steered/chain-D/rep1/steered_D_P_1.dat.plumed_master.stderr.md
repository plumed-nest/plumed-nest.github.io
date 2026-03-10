**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-D/rep1/steered_D_P_1.dat   
Download: [zipped raw stdout](steered_D_P_1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](steered_D_P_1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervm0kj6c:04504] *** Process received signal ***
[runnervm0kj6c:04504] Signal: Aborted (6)
[runnervm0kj6c:04504] Signal code:  (-6)
[runnervm0kj6c:04504] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fceff445330]
[runnervm0kj6c:04504] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fceff49eb2c]
[runnervm0kj6c:04504] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fceff44527e]
[runnervm0kj6c:04504] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fceff4288ff]
[runnervm0kj6c:04504] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fceff8a5ff5]
[runnervm0kj6c:04504] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fceff8bb0da]
[runnervm0kj6c:04504] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fceff8a5a55]
[runnervm0kj6c:04504] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fceff8a5a6f]
[runnervm0kj6c:04504] [ 8] plumed_master(+0x146dd)[0x5613a54456dd]
[runnervm0kj6c:04504] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fceff42a1ca]
[runnervm0kj6c:04504] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fceff42a28b]
[runnervm0kj6c:04504] [11] plumed_master(+0x15365)[0x5613a5446365]
[runnervm0kj6c:04504] *** End of error message ***
</pre>
{% endraw %}
