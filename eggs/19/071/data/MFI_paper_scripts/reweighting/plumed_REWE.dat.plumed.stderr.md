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
[fv-az789-879:67196] *** Process received signal ***
[fv-az789-879:67196] Signal: Aborted (6)
[fv-az789-879:67196] Signal code:  (-6)
[fv-az789-879:67196] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4f89c45330]
[fv-az789-879:67196] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4f89c9eb2c]
[fv-az789-879:67196] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4f89c4527e]
[fv-az789-879:67196] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4f89c288ff]
[fv-az789-879:67196] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4f8a0a5ff5]
[fv-az789-879:67196] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4f8a0bb0da]
[fv-az789-879:67196] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4f8a0a5a55]
[fv-az789-879:67196] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4f8a0a5a6f]
[fv-az789-879:67196] [ 8] plumed(+0x146dd)[0x5598f61406dd]
[fv-az789-879:67196] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4f89c2a1ca]
[fv-az789-879:67196] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4f89c2a28b]
[fv-az789-879:67196] [11] plumed(+0x15365)[0x5598f6141365]
[fv-az789-879:67196] *** End of error message ***
</pre>
{% endraw %}
