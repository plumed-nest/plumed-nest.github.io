**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/reweighting/plumed_REWE.dat   
(download [zipped raw stdout](plumed_REWE.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action METAD with label metad : cannot understand the following words from the input line : REWEIGHTING_NGRID=200, REWEIGHTING_NHILLS=10
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12363] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12363] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12363] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12363] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f107cd974b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12363] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f107cd97428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12363] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f107cd9902a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12363] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f107d3d184d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12363] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f107d3cf6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12363] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f107d3cf701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12363] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f107d3cf919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12363] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12363] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12363] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12363] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f107cd82830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12363] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12363] *** End of error message ***
</pre>
{% endraw %}
