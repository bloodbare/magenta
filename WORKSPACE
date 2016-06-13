new_http_archive(
  name = "pretty_midi",
  build_file = "pretty_midi.BUILD",
  url = "https://github.com/bloodbare/pretty-midi/archive/d3261bedcad82ae1420c655b0318130fec281c3b.tar.gz",
  sha256 = "4c529ee3ee01bd049da66c5a02b1bb02ef9f14f4e96a452dd6bd74dbf584a2ee",
  strip_prefix = "pretty-midi-d3261bedcad82ae1420c655b0318130fec281c3b/pretty_midi",
)

new_http_archive(
  name = "midi",
  build_file = "python_midi.BUILD",
  url = "https://github.com/vishnubob/python-midi/archive/abb85028c97b433f74621be899a0b399cd100aaa.tar.gz",
  sha256 = "e1f58e8e13109162fa4f3ba8053e434df68014317780d43e53d1ac6a1a798c0b",
  strip_prefix = "python-midi-abb85028c97b433f74621be899a0b399cd100aaa/src",
)

git_repository(
  name = "protobuf",
  remote = "https://github.com/google/protobuf",
  commit = "18a9140f3308272313a9642af58ab0051ac09fd2",
)

new_http_archive(
  name = "six_archive",
  build_file = "six.BUILD",
  url = "https://pypi.python.org/packages/source/s/six/six-1.10.0.tar.gz#md5=34eed507548117b2ab523ab14b2f8b55",
  sha256 = "105f8d68616f8248e24bf0e9372ef04d3cc10104f1980f54d57b2ce73a5ad56a",
  strip_prefix = "six-1.10.0"
)

bind(
  name = "six",
  actual = "@six_archive//:six",
)

bind(
    name = "python_headers",
    actual = "//util/python:python_headers",
)
