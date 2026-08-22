**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Native-Deprot/4-Steered/chain-A/rep2/steered_A_2.dat   
Download: [zipped raw stdout](steered_A_2.dat.plumed.stdout.txt.zip) - [zipped raw stderr](steered_A_2.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Deprot/ermsd_ref.pdb
[runnervm76f27:05311] *** Process received signal ***
[runnervm76f27:05311] Signal: Aborted (6)
[runnervm76f27:05311] Signal code:  (-6)
[runnervm76f27:05311] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa411a45330]
[runnervm76f27:05311] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa411a9ec0c]
[runnervm76f27:05311] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa411a4527e]
[runnervm76f27:05311] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa411a288ff]
[runnervm76f27:05311] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa411ea5ff5]
[runnervm76f27:05311] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa411ebb0da]
[runnervm76f27:05311] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa411ea5a55]
[runnervm76f27:05311] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa411ea5a6f]
[runnervm76f27:05311] [ 8] plumed(+0x146dd)[0x55f7423ec6dd]
[runnervm76f27:05311] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa411a2a1ca]
[runnervm76f27:05311] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa411a2a28b]
[runnervm76f27:05311] [11] plumed(+0x15365)[0x55f7423ed365]
[runnervm76f27:05311] *** End of error message ***
</pre>
{% endraw %}
