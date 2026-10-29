Certificate artwork (LIVOMYN Certificate of Participation, portrait 3:4):
  template_base.jpg - the certificate design WITHOUT its wording (border, ring,
                      ribbon, lines, CME seal, Charak and LIVOMYN logos),
                      2172 x 2896. REQUIRED.
  photo_ring.png    - the gold ring around the photo, 944 x 944, transparent
                      inside (photo hole, radius 412) and outside. Used on the
                      certificate, the photo preview and the camera overlay.
All wording is drawn by the app as real text, so it is sharp at any zoom:
  design wording - assets/fonts/LiberationSerif-*.ttf, LiberationSans-Bold.ttf
                   (same shapes and sizes as Times New Roman / Arial;
                   SIL Open Font License)
  doctor's name  - assets/fonts/GreatVibes-Regular.ttf
  date, number   - assets/fonts/NunitoSans-Bold.ttf
Text and positions are set in lib/features/flow/certificate_renderer.dart.
Old files template_base.png and photo_frame.png are no longer used - delete them.
