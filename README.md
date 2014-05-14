OTCD
====

Asterisk to OTRS daemon

# USAGE

* Change settings in config.xml and put it into /etc/otcd/config.xml
* Change domain in otcd. Somethin like this

        sed s/example.com/your.domain.org/g < otcd

Run daemon:
        
        cd /path/to/otcd/dir/
        ./otcd

# Dependencies
        
        Asterisk::AMI
        EV
        XML::Simple
        SOAP::Lite

Install it from CPAN:
        
        cpan install Asterisk::AMI
        cpan install EV
        cpan install XML::Simple
        cpan install SOAP::Lite

Or from you distro repositories
