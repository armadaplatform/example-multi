require 'open-uri'
armada_vagrantfile_path = File.join(Dir.tmpdir, 'ArmadaVagrantfile.rb')
IO.write(armada_vagrantfile_path, open('http://vagrant.armada.sh/ArmadaVagrantfile.rb').read)
load armada_vagrantfile_path

armada_vagrantfile :microservice_name => 'example-multi'
