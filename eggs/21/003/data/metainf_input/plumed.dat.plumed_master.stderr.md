**Project ID:** [plumID:21.003]({{ '/' | absolute_url }}eggs/21/003/)  
Stderr for source:  metainf_input/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az1374-933:11904] *** Process received signal ***
[fv-az1374-933:11904] Signal: Aborted (6)
[fv-az1374-933:11904] Signal code:  (-6)
[fv-az1374-933:11904] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdd4a845330]
[fv-az1374-933:11904] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdd4a89eb2c]
[fv-az1374-933:11904] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdd4a84527e]
[fv-az1374-933:11904] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdd4a8288ff]
[fv-az1374-933:11904] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdd4aca5ff5]
[fv-az1374-933:11904] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdd4acbb0da]
[fv-az1374-933:11904] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdd4aca5a55]
[fv-az1374-933:11904] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdd4aca5a6f]
[fv-az1374-933:11904] [ 8] plumed_master(+0x146dd)[0x5555af8036dd]
[fv-az1374-933:11904] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdd4a82a1ca]
[fv-az1374-933:11904] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdd4a82a28b]
[fv-az1374-933:11904] [11] plumed_master(+0x15365)[0x5555af804365]
[fv-az1374-933:11904] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label test2 : cannot understand the following words from the input line : SCALEINT=1680
[fv-az1374-933:11905] *** Process received signal ***
[fv-az1374-933:11905] Signal: Aborted (6)
[fv-az1374-933:11905] Signal code:  (-6)
[fv-az1374-933:11905] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff06f245330]
[fv-az1374-933:11905] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff06f29eb2c]
[fv-az1374-933:11905] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff06f24527e]
[fv-az1374-933:11905] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff06f2288ff]
[fv-az1374-933:11905] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff06f6a5ff5]
[fv-az1374-933:11905] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff06f6bb0da]
[fv-az1374-933:11905] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff06f6a5a55]
[fv-az1374-933:11905] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff06f6a5a6f]
[fv-az1374-933:11905] [ 8] plumed_master(+0x146dd)[0x56358e48c6dd]
[fv-az1374-933:11905] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff06f22a1ca]
[fv-az1374-933:11905] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff06f22a28b]
[fv-az1374-933:11905] [11] plumed_master(+0x15365)[0x56358e48d365]
[fv-az1374-933:11905] *** End of error message ***
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun noticed that process rank 0 with PID 0 on node fv-az1374-933 exited on signal 6 (Aborted).
--------------------------------------------------------------------------
</pre>
{% endraw %}
