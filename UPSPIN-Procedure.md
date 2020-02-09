# Upspin Setup Procedure
Manually setting up Upspin

## Prerequisite
**The following requirements are directly from [Upspin setup instruction](https://upspin.io/doc/server_setup.md) webpage**
To deploy an upspinserver you need to decide on values for:

An Internet domain to which you can add DNS records. (We will use example.com in this document.) Note that the domain need not be dedicated to your Upspin installation; it just acts as a name space inside which you can create Upspin users for administrative purposes.

+ Your Upspin user name (an email address). (We will use you@gmail.com in this document.) This user will be the administrator of your Upspin installation. The address may be under any domain, as long you can receive mail at that address.
+ The host name of the server on which upspinserver will run. (We will use upspin.example.com in this document.)

## Sign up for an Upspin account
+ Redirect to UI and filling out necessary info such as email address

## Set up Domain
+ Use the command below
> upspin setupdomain -domain=example.com

+ Obtain the given DNS record from command response
+ Add the DNS record to DNS list on your existing domain DNS entry
+ Type in the following command to check if the DNS record is successfully added
> host -t TXT example.com

## Build *Upspinserver* Binary

### Local Disk

### Cloud Services

## Set up Server and Deploy *Upspinserver* Binary

## Test Connectivity

## Config *Upspinserver*

## User's Guidance and Examples (Later)


