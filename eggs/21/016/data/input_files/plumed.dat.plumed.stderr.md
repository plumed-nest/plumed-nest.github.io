**Project ID:** [plumID:21.016]({{ '/' | absolute_url }}eggs/21/016/)  
Stderr for source:  input_files/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label saxs : cannot understand the following words from the input line : SCALEINT=1
[pkrvmxyh4eaekms:09845] *** Process received signal ***
[pkrvmxyh4eaekms:09845] Signal: Aborted (6)
[pkrvmxyh4eaekms:09845] Signal code:  (-6)
[pkrvmxyh4eaekms:09845] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3827045330]
[pkrvmxyh4eaekms:09845] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f382709eb2c]
[pkrvmxyh4eaekms:09845] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f382704527e]
[pkrvmxyh4eaekms:09845] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f38270288ff]
[pkrvmxyh4eaekms:09845] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f38274a5ff5]
[pkrvmxyh4eaekms:09845] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f38274bb0da]
[pkrvmxyh4eaekms:09845] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f38274a5a55]
[pkrvmxyh4eaekms:09845] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f38274a5a6f]
[pkrvmxyh4eaekms:09845] [ 8] plumed(+0x146dd)[0x55f3ca36d6dd]
[pkrvmxyh4eaekms:09845] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f382702a1ca]
[pkrvmxyh4eaekms:09845] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f382702a28b]
[pkrvmxyh4eaekms:09845] [11] plumed(+0x15365)[0x55f3ca36e365]
[pkrvmxyh4eaekms:09845] *** End of error message ***
</pre>
{% endraw %}
