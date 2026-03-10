**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-B/rep1/steered_B_P_1.dat   
Download: [zipped raw stdout](steered_B_P_1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](steered_B_P_1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervm0kj6c:04592] *** Process received signal ***
[runnervm0kj6c:04592] Signal: Aborted (6)
[runnervm0kj6c:04592] Signal code:  (-6)
[runnervm0kj6c:04592] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4d21045330]
[runnervm0kj6c:04592] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4d2109eb2c]
[runnervm0kj6c:04592] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4d2104527e]
[runnervm0kj6c:04592] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4d210288ff]
[runnervm0kj6c:04592] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4d214a5ff5]
[runnervm0kj6c:04592] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4d214bb0da]
[runnervm0kj6c:04592] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4d214a5a55]
[runnervm0kj6c:04592] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4d214a5a6f]
[runnervm0kj6c:04592] [ 8] plumed(+0x146dd)[0x55f22bd366dd]
[runnervm0kj6c:04592] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4d2102a1ca]
[runnervm0kj6c:04592] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4d2102a28b]
[runnervm0kj6c:04592] [11] plumed(+0x15365)[0x55f22bd37365]
[runnervm0kj6c:04592] *** End of error message ***
</pre>
{% endraw %}
