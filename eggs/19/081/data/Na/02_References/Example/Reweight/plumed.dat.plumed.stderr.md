**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/Reweight/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s13 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmgx7h7:11694] *** Process received signal ***
[runnervmgx7h7:11694] Signal: Aborted (6)
[runnervmgx7h7:11694] Signal code:  (-6)
[runnervmgx7h7:11694] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f09ee645330]
[runnervmgx7h7:11694] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f09ee69ec0c]
[runnervmgx7h7:11694] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f09ee64527e]
[runnervmgx7h7:11694] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f09ee6288ff]
[runnervmgx7h7:11694] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f09eeaa5ff5]
[runnervmgx7h7:11694] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f09eeabb0da]
[runnervmgx7h7:11694] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f09eeaa5a55]
[runnervmgx7h7:11694] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f09eeaa5a6f]
[runnervmgx7h7:11694] [ 8] plumed(+0x146dd)[0x55db7bacd6dd]
[runnervmgx7h7:11694] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f09ee62a1ca]
[runnervmgx7h7:11694] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f09ee62a28b]
[runnervmgx7h7:11694] [11] plumed(+0x15365)[0x55db7bace365]
[runnervmgx7h7:11694] *** End of error message ***
</pre>
{% endraw %}
