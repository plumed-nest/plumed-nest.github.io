**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/contacts.plumed   
Download: [zipped raw stdout](contacts.plumed.plumed.stdout.txt.zip) - [zipped raw stderr](contacts.plumed.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s41 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmvrwv9:08353] *** Process received signal ***
[runnervmvrwv9:08353] Signal: Aborted (6)
[runnervmvrwv9:08353] Signal code:  (-6)
[runnervmvrwv9:08353] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7252e45330]
[runnervmvrwv9:08353] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7252e9eb2c]
[runnervmvrwv9:08353] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7252e4527e]
[runnervmvrwv9:08353] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7252e288ff]
[runnervmvrwv9:08353] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f72532a5ff5]
[runnervmvrwv9:08353] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f72532bb0da]
[runnervmvrwv9:08353] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f72532a5a55]
[runnervmvrwv9:08353] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f72532a5a6f]
[runnervmvrwv9:08353] [ 8] plumed(+0x146dd)[0x563befc346dd]
[runnervmvrwv9:08353] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7252e2a1ca]
[runnervmvrwv9:08353] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7252e2a28b]
[runnervmvrwv9:08353] [11] plumed(+0x15365)[0x563befc35365]
[runnervmvrwv9:08353] *** End of error message ***
</pre>
{% endraw %}
