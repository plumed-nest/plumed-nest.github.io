**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s43 : missing SWITCH11 keyword
[pkrvmxyh4eaekms:14124] *** Process received signal ***
[pkrvmxyh4eaekms:14124] Signal: Aborted (6)
[pkrvmxyh4eaekms:14124] Signal code:  (-6)
[pkrvmxyh4eaekms:14124] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4ea6845330]
[pkrvmxyh4eaekms:14124] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4ea689eb2c]
[pkrvmxyh4eaekms:14124] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4ea684527e]
[pkrvmxyh4eaekms:14124] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4ea68288ff]
[pkrvmxyh4eaekms:14124] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4ea6ca5ff5]
[pkrvmxyh4eaekms:14124] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4ea6cbb0da]
[pkrvmxyh4eaekms:14124] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4ea6ca5a55]
[pkrvmxyh4eaekms:14124] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4ea6ca5a6f]
[pkrvmxyh4eaekms:14124] [ 8] plumed_master(+0x146dd)[0x563dfc72b6dd]
[pkrvmxyh4eaekms:14124] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4ea682a1ca]
[pkrvmxyh4eaekms:14124] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4ea682a28b]
[pkrvmxyh4eaekms:14124] [11] plumed_master(+0x15365)[0x563dfc72c365]
[pkrvmxyh4eaekms:14124] *** End of error message ***
</pre>
{% endraw %}
