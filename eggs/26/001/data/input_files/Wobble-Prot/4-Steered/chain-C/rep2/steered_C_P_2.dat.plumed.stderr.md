**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-C/rep2/steered_C_P_2.dat   
Download: [zipped raw stdout](steered_C_P_2.dat.plumed.stdout.txt.zip) - [zipped raw stderr](steered_C_P_2.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervm76f27:04480] *** Process received signal ***
[runnervm76f27:04480] Signal: Aborted (6)
[runnervm76f27:04480] Signal code:  (-6)
[runnervm76f27:04480] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f62f0445330]
[runnervm76f27:04480] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f62f049ec0c]
[runnervm76f27:04480] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f62f044527e]
[runnervm76f27:04480] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f62f04288ff]
[runnervm76f27:04480] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f62f08a5ff5]
[runnervm76f27:04480] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f62f08bb0da]
[runnervm76f27:04480] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f62f08a5a55]
[runnervm76f27:04480] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f62f08a5a6f]
[runnervm76f27:04480] [ 8] plumed(+0x146dd)[0x55f40df7a6dd]
[runnervm76f27:04480] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f62f042a1ca]
[runnervm76f27:04480] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f62f042a28b]
[runnervm76f27:04480] [11] plumed(+0x15365)[0x55f40df7b365]
[runnervm76f27:04480] *** End of error message ***
</pre>
{% endraw %}
