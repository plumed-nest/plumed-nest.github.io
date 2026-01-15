**Project ID:** [plumID:25.009]({{ '/' | absolute_url }}eggs/25/009/)  
Stderr for source:  T1_MetaD/hills/plumed-reweight-time-dependent-w0.dat   
Download: [zipped raw stdout](plumed-reweight-time-dependent-w0.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-reweight-time-dependent-w0.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @23 : keyword ARG is compulsory for this action
[runnervmmtnos:31621] *** Process received signal ***
[runnervmmtnos:31621] Signal: Aborted (6)
[runnervmmtnos:31621] Signal code:  (-6)
[runnervmmtnos:31621] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f99dc245330]
[runnervmmtnos:31621] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f99dc29eb2c]
[runnervmmtnos:31621] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f99dc24527e]
[runnervmmtnos:31621] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f99dc2288ff]
[runnervmmtnos:31621] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f99dc6a5ff5]
[runnervmmtnos:31621] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f99dc6bb0da]
[runnervmmtnos:31621] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f99dc6a5a55]
[runnervmmtnos:31621] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f99dc6a5a6f]
[runnervmmtnos:31621] [ 8] plumed_master(+0x146dd)[0x55a7ccf316dd]
[runnervmmtnos:31621] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f99dc22a1ca]
[runnervmmtnos:31621] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f99dc22a28b]
[runnervmmtnos:31621] [11] plumed_master(+0x15365)[0x55a7ccf32365]
[runnervmmtnos:31621] *** End of error message ***
</pre>
{% endraw %}
