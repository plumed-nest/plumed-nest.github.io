**Project ID:** [plumID:21.003]({{ '/' | absolute_url }}eggs/21/003/)  
Stderr for source:  metainf_input/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az787-589:65582] *** Process received signal ***
[fv-az787-589:65582] Signal: Aborted (6)
[fv-az787-589:65582] Signal code:  (-6)
[fv-az787-589:65582] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f75adc45330]
[fv-az787-589:65582] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f75adc9eb2c]
[fv-az787-589:65582] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f75adc4527e]
[fv-az787-589:65582] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f75adc288ff]
[fv-az787-589:65582] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f75ae0a5ff5]
[fv-az787-589:65582] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f75ae0bb0da]
[fv-az787-589:65582] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f75ae0a5a55]
[fv-az787-589:65582] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f75ae0a5a6f]
[fv-az787-589:65582] [ 8] plumed(+0x146dd)[0x559f111606dd]
[fv-az787-589:65582] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f75adc2a1ca]
[fv-az787-589:65582] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f75adc2a28b]
[fv-az787-589:65582] [11] plumed(+0x15365)[0x559f11161365]
[fv-az787-589:65582] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az787-589:65583] *** Process received signal ***
[fv-az787-589:65583] Signal: Aborted (6)
[fv-az787-589:65583] Signal code:  (-6)
[fv-az787-589:65583] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9198645330]
[fv-az787-589:65583] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f919869eb2c]
[fv-az787-589:65583] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f919864527e]
[fv-az787-589:65583] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f91986288ff]
[fv-az787-589:65583] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9198aa5ff5]
[fv-az787-589:65583] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9198abb0da]
[fv-az787-589:65583] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9198aa5a55]
[fv-az787-589:65583] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9198aa5a6f]
[fv-az787-589:65583] [ 8] plumed(+0x146dd)[0x55dec896d6dd]
[fv-az787-589:65583] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f919862a1ca]
[fv-az787-589:65583] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f919862a28b]
[fv-az787-589:65583] [11] plumed(+0x15365)[0x55dec896e365]
[fv-az787-589:65583] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node fv-az787-589 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
