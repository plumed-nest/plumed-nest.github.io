**Project ID:** [plumID:21.003]({{ '/' | absolute_url }}eggs/21/003/)  
Stderr for source:  metainf_input/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT
[runnervmi13qx:40137] *** Process received signal ***
[runnervmi13qx:40137] Signal: Aborted (6)
[runnervmi13qx:40137] Signal code:  (-6)
[runnervmi13qx:40137] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f88e2045330]
[runnervmi13qx:40137] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f88e209eb2c]
[runnervmi13qx:40137] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f88e204527e]
[runnervmi13qx:40137] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f88e20288ff]
[runnervmi13qx:40137] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f88e24a5ff5]
[runnervmi13qx:40137] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f88e24bb0da]
[runnervmi13qx:40137] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f88e24a5a55]
[runnervmi13qx:40137] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f88e24a5a6f]
[runnervmi13qx:40137] [ 8] plumed_master(+0x146dd)[0x55557ceb26dd]
[runnervmi13qx:40137] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f88e202a1ca]
[runnervmi13qx:40137] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f88e202a28b]
[runnervmi13qx:40137] [11] plumed_master(+0x15365)[0x55557ceb3365]
[runnervmi13qx:40137] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT
[runnervmi13qx:40138] *** Process received signal ***
[runnervmi13qx:40138] Signal: Aborted (6)
[runnervmi13qx:40138] Signal code:  (-6)
[runnervmi13qx:40138] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f182f245330]
[runnervmi13qx:40138] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f182f29eb2c]
[runnervmi13qx:40138] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f182f24527e]
[runnervmi13qx:40138] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f182f2288ff]
[runnervmi13qx:40138] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f182f6a5ff5]
[runnervmi13qx:40138] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f182f6bb0da]
[runnervmi13qx:40138] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f182f6a5a55]
[runnervmi13qx:40138] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f182f6a5a6f]
[runnervmi13qx:40138] [ 8] plumed_master(+0x146dd)[0x55f286ca26dd]
[runnervmi13qx:40138] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f182f22a1ca]
[runnervmi13qx:40138] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f182f22a28b]
[runnervmi13qx:40138] [11] plumed_master(+0x15365)[0x55f286ca3365]
[runnervmi13qx:40138] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node runnervmi13qx exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
