**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-C/rep2/equil_C_P_2.dat   
Download: [zipped raw stdout](equil_C_P_2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](equil_C_P_2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmeorf1:04994] *** Process received signal ***
[runnervmeorf1:04994] Signal: Aborted (6)
[runnervmeorf1:04994] Signal code:  (-6)
[runnervmeorf1:04994] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f21fc245330]
[runnervmeorf1:04994] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f21fc29eb2c]
[runnervmeorf1:04994] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f21fc24527e]
[runnervmeorf1:04994] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f21fc2288ff]
[runnervmeorf1:04994] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f21fc6a5ff5]
[runnervmeorf1:04994] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f21fc6bb0da]
[runnervmeorf1:04994] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f21fc6a5a55]
[runnervmeorf1:04994] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f21fc6a5a6f]
[runnervmeorf1:04994] [ 8] plumed_master(+0x146dd)[0x5563b60a76dd]
[runnervmeorf1:04994] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f21fc22a1ca]
[runnervmeorf1:04994] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f21fc22a28b]
[runnervmeorf1:04994] [11] plumed_master(+0x15365)[0x5563b60a8365]
[runnervmeorf1:04994] *** End of error message ***
</pre>
{% endraw %}
