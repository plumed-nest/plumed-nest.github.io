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
[runnervmkj6or:07509] *** Process received signal ***
[runnervmkj6or:07509] Signal: Aborted (6)
[runnervmkj6or:07509] Signal code:  (-6)
[runnervmkj6or:07509] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd734045330]
[runnervmkj6or:07509] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd73409eb2c]
[runnervmkj6or:07509] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd73404527e]
[runnervmkj6or:07509] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd7340288ff]
[runnervmkj6or:07509] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd7344a5ff5]
[runnervmkj6or:07509] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd7344bb0da]
[runnervmkj6or:07509] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd7344a5a55]
[runnervmkj6or:07509] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd7344a5a6f]
[runnervmkj6or:07509] [ 8] plumed_master(+0x146dd)[0x56233ded56dd]
[runnervmkj6or:07509] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd73402a1ca]
[runnervmkj6or:07509] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd73402a28b]
[runnervmkj6or:07509] [11] plumed_master(+0x15365)[0x56233ded6365]
[runnervmkj6or:07509] *** End of error message ***
</pre>
{% endraw %}
