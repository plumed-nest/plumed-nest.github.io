**Project ID:** [plumID:25.029]({{ '/' | absolute_url }}eggs/25/029/)  
Stderr for source:  ./crys/4-reweight_crys.dat   
Download: [zipped raw stdout](4-reweight_crys.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](4-reweight_crys.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @46 : keyword ARG is compulsory for this action
[runnervmeorf1:04226] *** Process received signal ***
[runnervmeorf1:04226] Signal: Aborted (6)
[runnervmeorf1:04226] Signal code:  (-6)
[runnervmeorf1:04226] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd8f4445330]
[runnervmeorf1:04226] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd8f449eb2c]
[runnervmeorf1:04226] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd8f444527e]
[runnervmeorf1:04226] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd8f44288ff]
[runnervmeorf1:04226] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd8f48a5ff5]
[runnervmeorf1:04226] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd8f48bb0da]
[runnervmeorf1:04226] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd8f48a5a55]
[runnervmeorf1:04226] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd8f48a5a6f]
[runnervmeorf1:04226] [ 8] plumed_master(+0x146dd)[0x55d6987ea6dd]
[runnervmeorf1:04226] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd8f442a1ca]
[runnervmeorf1:04226] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd8f442a28b]
[runnervmeorf1:04226] [11] plumed_master(+0x15365)[0x55d6987eb365]
[runnervmeorf1:04226] *** End of error message ***
</pre>
{% endraw %}
