CodeIgniter ElephantIO Library
=================

 Requirements
  ------------
  1. PHP 5+
  2. [CodeIgniter 2.0+](http://codeigniter.com)
  3. [node.js server](http://nodejs.org/)
  4. [socket.io](http://socket.io/)
  



CONFIG
```
$config['socketIOUrl'] = "http://localhost:3030";
 
```

EXAMPLES
```
  // load Library
  $this->load->library('elephantio/elephantio');
  
  //Example
  $this->elephantio->init();
  $this->elephantio->emit('foo', 'bar');
  $this->elephantio->close();
 
```


 License
  -------
  This library is released under the MIT license.
  
  
 Thanks
  -------
  [Ludovic Barreca](http://elephant.io/)
  
