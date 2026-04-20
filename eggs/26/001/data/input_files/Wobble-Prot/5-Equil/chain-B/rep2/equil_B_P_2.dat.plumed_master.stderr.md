**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-B/rep2/equil_B_P_2.dat   
Download: [zipped raw stdout](equil_B_P_2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](equil_B_P_2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmeorf1:05251] *** Process received signal ***
[runnervmeorf1:05251] Signal: Aborted (6)
[runnervmeorf1:05251] Signal code:  (-6)
[runnervmeorf1:05251] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc93a445330]
[runnervmeorf1:05251] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc93a49eb2c]
[runnervmeorf1:05251] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc93a44527e]
[runnervmeorf1:05251] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc93a4288ff]
[runnervmeorf1:05251] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc93a8a5ff5]
[runnervmeorf1:05251] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc93a8bb0da]
[runnervmeorf1:05251] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc93a8a5a55]
[runnervmeorf1:05251] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc93a8a5a6f]
[runnervmeorf1:05251] [ 8] plumed_master(+0x146dd)[0x55940f28b6dd]
[runnervmeorf1:05251] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc93a42a1ca]
[runnervmeorf1:05251] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc93a42a28b]
[runnervmeorf1:05251] [11] plumed_master(+0x15365)[0x55940f28c365]
[runnervmeorf1:05251] *** End of error message ***
</pre>
{% endraw %}
