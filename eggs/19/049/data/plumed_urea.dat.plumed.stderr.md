**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s41 : missing SWITCH11 keyword
[pkrvmxyh4eaekms:14108] *** Process received signal ***
[pkrvmxyh4eaekms:14108] Signal: Aborted (6)
[pkrvmxyh4eaekms:14108] Signal code:  (-6)
[pkrvmxyh4eaekms:14108] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff976845330]
[pkrvmxyh4eaekms:14108] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff97689eb2c]
[pkrvmxyh4eaekms:14108] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff97684527e]
[pkrvmxyh4eaekms:14108] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff9768288ff]
[pkrvmxyh4eaekms:14108] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff976ca5ff5]
[pkrvmxyh4eaekms:14108] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff976cbb0da]
[pkrvmxyh4eaekms:14108] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff976ca5a55]
[pkrvmxyh4eaekms:14108] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff976ca5a6f]
[pkrvmxyh4eaekms:14108] [ 8] plumed(+0x146dd)[0x55d852b566dd]
[pkrvmxyh4eaekms:14108] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff97682a1ca]
[pkrvmxyh4eaekms:14108] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff97682a28b]
[pkrvmxyh4eaekms:14108] [11] plumed(+0x15365)[0x55d852b57365]
[pkrvmxyh4eaekms:14108] *** End of error message ***
</pre>
{% endraw %}
