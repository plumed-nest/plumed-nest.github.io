**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action PRINT with label @333 : cannot use argument parabeta0_both.struct-1 in input as not all elements are computed
[pkrvmxyh4eaekms:05801] *** Process received signal ***
[pkrvmxyh4eaekms:05801] Signal: Aborted (6)
[pkrvmxyh4eaekms:05801] Signal code:  (-6)
[pkrvmxyh4eaekms:05801] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f032d645330]
[pkrvmxyh4eaekms:05801] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f032d69eb2c]
[pkrvmxyh4eaekms:05801] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f032d64527e]
[pkrvmxyh4eaekms:05801] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f032d6288ff]
[pkrvmxyh4eaekms:05801] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f032daa5ff5]
[pkrvmxyh4eaekms:05801] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f032dabb0da]
[pkrvmxyh4eaekms:05801] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f032daa5a55]
[pkrvmxyh4eaekms:05801] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f032daa5a6f]
[pkrvmxyh4eaekms:05801] [ 8] plumed_master(+0x146dd)[0x5627250dc6dd]
[pkrvmxyh4eaekms:05801] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f032d62a1ca]
[pkrvmxyh4eaekms:05801] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f032d62a28b]
[pkrvmxyh4eaekms:05801] [11] plumed_master(+0x15365)[0x5627250dd365]
[pkrvmxyh4eaekms:05801] *** End of error message ***
</pre>
{% endraw %}
