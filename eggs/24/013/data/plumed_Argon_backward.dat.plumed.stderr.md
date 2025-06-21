**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_backward.dat   
Download: [zipped raw stdout](plumed_Argon_backward.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_backward.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[pkrvmxyh4eaekms:06228] *** Process received signal ***
[pkrvmxyh4eaekms:06228] Signal: Aborted (6)
[pkrvmxyh4eaekms:06228] Signal code:  (-6)
[pkrvmxyh4eaekms:06228] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd89a845330]
[pkrvmxyh4eaekms:06228] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd89a89eb2c]
[pkrvmxyh4eaekms:06228] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd89a84527e]
[pkrvmxyh4eaekms:06228] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd89a8288ff]
[pkrvmxyh4eaekms:06228] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd89aca5ff5]
[pkrvmxyh4eaekms:06228] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd89acbb0da]
[pkrvmxyh4eaekms:06228] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd89aca5a55]
[pkrvmxyh4eaekms:06228] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd89aca5a6f]
[pkrvmxyh4eaekms:06228] [ 8] plumed(+0x146dd)[0x5582711426dd]
[pkrvmxyh4eaekms:06228] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd89a82a1ca]
[pkrvmxyh4eaekms:06228] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd89a82a28b]
[pkrvmxyh4eaekms:06228] [11] plumed(+0x15365)[0x558271143365]
[pkrvmxyh4eaekms:06228] *** End of error message ***
</pre>
{% endraw %}
