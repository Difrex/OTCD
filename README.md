OTCD
====

Asterisk to OTRS daemon

# USAGE

Change settings in config.xml and put it into /etc/otcd/config.xml

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
