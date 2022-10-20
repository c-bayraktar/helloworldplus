 ![image](https://user-images.githubusercontent.com/115998130/196672612-8816b4f8-02f7-4571-a9b3-c1625abf3a40.png)

[![pip](https://img.shields.io/badge/pip-install%20helloworldplus-blue.svg)](https://test.pypi.org/project/example-package-c-bayraktar/)
[![Documentation](https://img.shields.io/badge/Documentation-%E2%9C%93-blue.svg)](https://helloworldplus.readthedocs.io/en/latest/)


# helloworld+
helloworld+ is a simple mock package to obtain the classic phrase 'Hello World!' and its variation(s) depending on your research interest. As of the moment there are only three research interests to choose from:  
(1) exoplanets,  
(2) exomoons, and  
(3) solar. 


Install
```ruby
pip install -i https://test.pypi.org/simple/ example-package-c-bayraktar --upgrade
```
and import the package
```ruby
from example_package_c_bayraktar import project_example as pe
```
Enter your research interest (see above) in the function to get the result, e.g.
```ruby
pe.target('exoplanets')
```
