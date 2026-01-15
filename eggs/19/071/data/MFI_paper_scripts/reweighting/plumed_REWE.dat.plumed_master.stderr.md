**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/reweighting/plumed_REWE.dat   
Download: [zipped raw stdout](plumed_REWE.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_REWE.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : cannot understand the following words from the input line : REWEIGHTING_NGRID, REWEIGHTING_NHILLS
[runnervmmtnos:39270] *** Process received signal ***
[runnervmmtnos:39270] Signal: Aborted (6)
[runnervmmtnos:39270] Signal code:  (-6)
[runnervmmtnos:39270] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0fde245330]
[runnervmmtnos:39270] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0fde29eb2c]
[runnervmmtnos:39270] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0fde24527e]
[runnervmmtnos:39270] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0fde2288ff]
[runnervmmtnos:39270] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0fde6a5ff5]
[runnervmmtnos:39270] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0fde6bb0da]
[runnervmmtnos:39270] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0fde6a5a55]
[runnervmmtnos:39270] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0fde6a5a6f]
[runnervmmtnos:39270] [ 8] plumed_master(+0x146dd)[0x560408ea56dd]
[runnervmmtnos:39270] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0fde22a1ca]
[runnervmmtnos:39270] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0fde22a28b]
[runnervmmtnos:39270] [11] plumed_master(+0x15365)[0x560408ea6365]
[runnervmmtnos:39270] *** End of error message ***
</pre>
{% endraw %}
