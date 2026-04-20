**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-A/rep2/steered_A_P_2.dat   
Download: [zipped raw stdout](steered_A_P_2.dat.plumed.stdout.txt.zip) - [zipped raw stderr](steered_A_P_2.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmeorf1:04407] *** Process received signal ***
[runnervmeorf1:04407] Signal: Aborted (6)
[runnervmeorf1:04407] Signal code:  (-6)
[runnervmeorf1:04407] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffbd1045330]
[runnervmeorf1:04407] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffbd109eb2c]
[runnervmeorf1:04407] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffbd104527e]
[runnervmeorf1:04407] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffbd10288ff]
[runnervmeorf1:04407] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffbd14a5ff5]
[runnervmeorf1:04407] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffbd14bb0da]
[runnervmeorf1:04407] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffbd14a5a55]
[runnervmeorf1:04407] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffbd14a5a6f]
[runnervmeorf1:04407] [ 8] plumed(+0x146dd)[0x56386076f6dd]
[runnervmeorf1:04407] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffbd102a1ca]
[runnervmeorf1:04407] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffbd102a28b]
[runnervmeorf1:04407] [11] plumed(+0x15365)[0x563860770365]
[runnervmeorf1:04407] *** End of error message ***
</pre>
{% endraw %}
