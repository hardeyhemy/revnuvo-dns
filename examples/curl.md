# Verify Domain

curl -X POST https://dns.revnuvo.site/domain/verify 
-H "Content-Type: application/json" 
-d '{"domain":"stripe.com"}'

# Resolve DNS

curl -X POST https://dns.revnuvo.site/domain/dns 
-H "Content-Type: application/json" 
-d '{"domain":"stripe.com"}'
