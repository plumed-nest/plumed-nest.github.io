**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/reweighting/plumed_REWE.dat   
Download: [zipped raw stdout](plumed_REWE.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_REWE.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : cannot understand the following words from the input line : REWEIGHTING_NGRID=200, REWEIGHTING_NHILLS=10
[runnervmkj6or:07494] *** Process received signal ***
[runnervmkj6or:07494] Signal: Aborted (6)
[runnervmkj6or:07494] Signal code:  (-6)
[runnervmkj6or:07494] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdb3ea45330]
[runnervmkj6or:07494] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdb3ea9eb2c]
[runnervmkj6or:07494] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdb3ea4527e]
[runnervmkj6or:07494] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdb3ea288ff]
[runnervmkj6or:07494] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdb3eea5ff5]
[runnervmkj6or:07494] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdb3eebb0da]
[runnervmkj6or:07494] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdb3eea5a55]
[runnervmkj6or:07494] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdb3eea5a6f]
[runnervmkj6or:07494] [ 8] plumed(+0x146dd)[0x55892a1056dd]
[runnervmkj6or:07494] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdb3ea2a1ca]
[runnervmkj6or:07494] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdb3ea2a28b]
[runnervmkj6or:07494] [11] plumed(+0x15365)[0x55892a106365]
[runnervmkj6or:07494] *** End of error message ***
</pre>
{% endraw %}
