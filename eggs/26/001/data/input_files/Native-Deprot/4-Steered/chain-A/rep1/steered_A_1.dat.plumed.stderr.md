**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Native-Deprot/4-Steered/chain-A/rep1/steered_A_1.dat   
Download: [zipped raw stdout](steered_A_1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](steered_A_1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Deprot/ermsd_ref.pdb
[runnervm0kj6c:05162] *** Process received signal ***
[runnervm0kj6c:05162] Signal: Aborted (6)
[runnervm0kj6c:05162] Signal code:  (-6)
[runnervm0kj6c:05162] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4ef1a45330]
[runnervm0kj6c:05162] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4ef1a9eb2c]
[runnervm0kj6c:05162] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4ef1a4527e]
[runnervm0kj6c:05162] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4ef1a288ff]
[runnervm0kj6c:05162] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4ef1ea5ff5]
[runnervm0kj6c:05162] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4ef1ebb0da]
[runnervm0kj6c:05162] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4ef1ea5a55]
[runnervm0kj6c:05162] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4ef1ea5a6f]
[runnervm0kj6c:05162] [ 8] plumed(+0x146dd)[0x56116258a6dd]
[runnervm0kj6c:05162] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4ef1a2a1ca]
[runnervm0kj6c:05162] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4ef1a2a28b]
[runnervm0kj6c:05162] [11] plumed(+0x15365)[0x56116258b365]
[runnervm0kj6c:05162] *** End of error message ***
</pre>
{% endraw %}
