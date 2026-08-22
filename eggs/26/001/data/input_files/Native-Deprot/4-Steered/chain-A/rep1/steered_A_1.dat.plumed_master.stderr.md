**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Native-Deprot/4-Steered/chain-A/rep1/steered_A_1.dat   
Download: [zipped raw stdout](steered_A_1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](steered_A_1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Deprot/ermsd_ref.pdb
[runnervm76f27:05380] *** Process received signal ***
[runnervm76f27:05380] Signal: Aborted (6)
[runnervm76f27:05380] Signal code:  (-6)
[runnervm76f27:05380] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0b1c845330]
[runnervm76f27:05380] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0b1c89ec0c]
[runnervm76f27:05380] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0b1c84527e]
[runnervm76f27:05380] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0b1c8288ff]
[runnervm76f27:05380] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0b1cca5ff5]
[runnervm76f27:05380] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0b1ccbb0da]
[runnervm76f27:05380] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0b1cca5a55]
[runnervm76f27:05380] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0b1cca5a6f]
[runnervm76f27:05380] [ 8] plumed_master(+0x146dd)[0x555ff7ff56dd]
[runnervm76f27:05380] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0b1c82a1ca]
[runnervm76f27:05380] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0b1c82a28b]
[runnervm76f27:05380] [11] plumed_master(+0x15365)[0x555ff7ff6365]
[runnervm76f27:05380] *** End of error message ***
</pre>
{% endraw %}
