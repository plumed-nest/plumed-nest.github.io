**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/Reweight/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @29 : keyword ARG is compulsory for this action
[runnervmmklqx:11892] *** Process received signal ***
[runnervmmklqx:11892] Signal: Aborted (6)
[runnervmmklqx:11892] Signal code:  (-6)
[runnervmmklqx:11892] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd6c8245330]
[runnervmmklqx:11892] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd6c829eb2c]
[runnervmmklqx:11892] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd6c824527e]
[runnervmmklqx:11892] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd6c82288ff]
[runnervmmklqx:11892] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd6c86a5ff5]
[runnervmmklqx:11892] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd6c86bb0da]
[runnervmmklqx:11892] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd6c86a5a55]
[runnervmmklqx:11892] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd6c86a5a6f]
[runnervmmklqx:11892] [ 8] plumed_master(+0x146dd)[0x55a77c56f6dd]
[runnervmmklqx:11892] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd6c822a1ca]
[runnervmmklqx:11892] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd6c822a28b]
[runnervmmklqx:11892] [11] plumed_master(+0x15365)[0x55a77c570365]
[runnervmmklqx:11892] *** End of error message ***
</pre>
{% endraw %}
