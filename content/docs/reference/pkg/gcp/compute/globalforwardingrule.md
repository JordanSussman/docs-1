
---
title: "GlobalForwardingRule"
block_external_search_index: true
---



Represents a GlobalForwardingRule resource. Global forwarding rules are
used to forward traffic to the correct load balancer for HTTP load
balancing. Global forwarding rules can only be used for HTTP load
balancing.

For more information, see
https://cloud.google.com/compute/docs/load-balancing/http/

> This content is derived from https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/compute_global_forwarding_rule.html.markdown.



## Create a GlobalForwardingRule Resource

{{< chooser language "javascript,typescript,python,go,csharp" / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">new </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/gcp/compute/#GlobalForwardingRule">GlobalForwardingRule</a></span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">args</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/gcp/compute/#GlobalForwardingRuleArgs">GlobalForwardingRuleArgs</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">pulumi.CustomResourceOptions</a></span><span class="p">);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">def </span><span class="nf">GlobalForwardingRule</span><span class="p">(resource_name, opts=None, </span>description=None<span class="p">, </span>ip_address=None<span class="p">, </span>ip_protocol=None<span class="p">, </span>ip_version=None<span class="p">, </span>labels=None<span class="p">, </span>load_balancing_scheme=None<span class="p">, </span>metadata_filters=None<span class="p">, </span>name=None<span class="p">, </span>network=None<span class="p">, </span>port_range=None<span class="p">, </span>project=None<span class="p">, </span>target=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>NewGlobalForwardingRule<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">pulumi.Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">args</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-gcp/sdk/go/gcp/compute?tab=doc#GlobalForwardingRuleArgs">GlobalForwardingRuleArgs</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">pulumi.ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-gcp/sdk/go/gcp/compute?tab=doc#GlobalForwardingRule">GlobalForwardingRule</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Gcp/Pulumi.Gcp.Compute.GlobalForwardingRule.html">GlobalForwardingRule</a></span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Gcp/Pulumi.Gcp.Compute.GlobalForwardingRuleArgs.html">GlobalForwardingRuleArgs</a></span> <span class="nx">args<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language nodejs %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language csharp %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

#### Resource Arguments




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}An optional description of this resource. Provide this property when you create the resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ip<wbr>Address</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The IP address that this forwarding rule is serving on behalf of. Addresses are restricted based on the forwarding
rule's load balancing scheme (EXTERNAL or INTERNAL) and scope (global or regional). When the load balancing scheme is
EXTERNAL, for global forwarding rules, the address must be a global IP, and for regional forwarding rules, the address
must live in the same region as the forwarding rule. If this field is empty, an ephemeral IPv4 address from the same
scope (global or regional) will be assigned. A regional forwarding rule supports IPv4 only. A global forwarding rule
supports either IPv4 or IPv6. When the load balancing scheme is INTERNAL, this can only be an RFC 1918 IP address
belonging to the network/subnet configured for the forwarding rule. By default, if this field is empty, an ephemeral
internal IP address will be automatically allocated from the IP range of the subnet or network configured for this
forwarding rule. An address must be specified by a literal IP address. ~> **NOTE**: While the API allows you to specify
various resource paths for an address resource instead, Terraform requires this to specifically be an IP address to
avoid needing to fetching the IP address from resource paths on refresh or unnecessary diffs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ip<wbr>Protocol</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The IP protocol to which this rule applies. Valid options are TCP, UDP, ESP, AH, SCTP or ICMP. When the load balancing
scheme is INTERNAL_SELF_MANAGED, only TCP is valid.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ip<wbr>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The IP Version that will be used by this global forwarding rule. Valid options are IPV4 or IPV6.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary<string, string>?</span>
    </dt>
    <dd>{{% md %}}Labels to apply to this forwarding rule. A list of key->value pairs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Load<wbr>Balancing<wbr>Scheme</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}This signifies what the GlobalForwardingRule will be used for. The value of INTERNAL_SELF_MANAGED means that this will
be used for Internal Global HTTP(S) LB. The value of EXTERNAL means that this will be used for External Global Load
Balancing (HTTP(S) LB, External TCP/UDP LB, SSL Proxy) NOTE: Currently global forwarding rules cannot be used for
INTERNAL load balancing.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Metadata<wbr>Filters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#globalforwardingrulemetadatafilter">List&lt;Global<wbr>Forwarding<wbr>Rule<wbr>Metadata<wbr>Filter<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}Opaque filter criteria used by Loadbalancer to restrict routing configuration to a limited set xDS compliant clients. In
their xDS requests to Loadbalancer, xDS clients present node metadata. If a match takes place, the relevant routing
configuration is made available to those proxies. For each metadataFilter in this list, if its filterMatchCriteria is
set to MATCH_ANY, at least one of the filterLabels must match the corresponding label provided in the metadata. If its
filterMatchCriteria is set to MATCH_ALL, then all of its filterLabels must match with corresponding labels in the
provided metadata. metadataFilters specified here can be overridden by those specified in the UrlMap that this
ForwardingRule references. metadataFilters only applies to Loadbalancers that have their loadBalancingScheme set to
INTERNAL_SELF_MANAGED.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Name of the resource; provided by the client when the resource is created. The name must be 1-63 characters long, and
comply with RFC1035. Specifically, the name must be 1-63 characters long and match the regular expression
'[a-z]([-a-z0-9]*[a-z0-9])?' which means the first character must be a lowercase letter, and all following characters
must be a dash, lowercase letter, or digit, except the last character, which cannot be a dash.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Network</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}This field is not used for external load balancing. For INTERNAL_SELF_MANAGED load balancing, this field identifies the
network that the load balanced IP should belong to for this global forwarding rule. If this field is not specified, the
default network will be used.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Port<wbr>Range</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}This field is used along with the target field for TargetHttpProxy, TargetHttpsProxy, TargetSslProxy, TargetTcpProxy,
TargetVpnGateway, TargetPool, TargetInstance. Applicable only when IPProtocol is TCP, UDP, or SCTP, only packets
addressed to ports in the specified range will be forwarded to target. Forwarding rules with the same [IPAddress,
IPProtocol] pair must have disjoint port ranges. Some types of forwarding target have constraints on the acceptable
ports: * TargetHttpProxy: 80, 8080 * TargetHttpsProxy: 443 * TargetTcpProxy: 25, 43, 110, 143, 195, 443, 465, 587, 700,
993, 995, 1883, 5222 * TargetSslProxy: 25, 43, 110, 143, 195, 443, 465, 587, 700, 993, 995, 1883, 5222 *
TargetVpnGateway: 500, 4500
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Project</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Target</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The URL of the target resource to receive the matched traffic. The forwarded traffic must be of a type appropriate to
the target object. For INTERNAL_SELF_MANAGED load balancing, only HTTP and HTTPS targets are valid.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}An optional description of this resource. Provide this property when you create the resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ip<wbr>Address</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The IP address that this forwarding rule is serving on behalf of. Addresses are restricted based on the forwarding
rule's load balancing scheme (EXTERNAL or INTERNAL) and scope (global or regional). When the load balancing scheme is
EXTERNAL, for global forwarding rules, the address must be a global IP, and for regional forwarding rules, the address
must live in the same region as the forwarding rule. If this field is empty, an ephemeral IPv4 address from the same
scope (global or regional) will be assigned. A regional forwarding rule supports IPv4 only. A global forwarding rule
supports either IPv4 or IPv6. When the load balancing scheme is INTERNAL, this can only be an RFC 1918 IP address
belonging to the network/subnet configured for the forwarding rule. By default, if this field is empty, an ephemeral
internal IP address will be automatically allocated from the IP range of the subnet or network configured for this
forwarding rule. An address must be specified by a literal IP address. ~> **NOTE**: While the API allows you to specify
various resource paths for an address resource instead, Terraform requires this to specifically be an IP address to
avoid needing to fetching the IP address from resource paths on refresh or unnecessary diffs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ip<wbr>Protocol</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The IP protocol to which this rule applies. Valid options are TCP, UDP, ESP, AH, SCTP or ICMP. When the load balancing
scheme is INTERNAL_SELF_MANAGED, only TCP is valid.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ip<wbr>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The IP Version that will be used by this global forwarding rule. Valid options are IPV4 or IPV6.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]string</span>
    </dt>
    <dd>{{% md %}}Labels to apply to this forwarding rule. A list of key->value pairs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Load<wbr>Balancing<wbr>Scheme</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}This signifies what the GlobalForwardingRule will be used for. The value of INTERNAL_SELF_MANAGED means that this will
be used for Internal Global HTTP(S) LB. The value of EXTERNAL means that this will be used for External Global Load
Balancing (HTTP(S) LB, External TCP/UDP LB, SSL Proxy) NOTE: Currently global forwarding rules cannot be used for
INTERNAL load balancing.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Metadata<wbr>Filters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#globalforwardingrulemetadatafilter">[]Global<wbr>Forwarding<wbr>Rule<wbr>Metadata<wbr>Filter</a></span>
    </dt>
    <dd>{{% md %}}Opaque filter criteria used by Loadbalancer to restrict routing configuration to a limited set xDS compliant clients. In
their xDS requests to Loadbalancer, xDS clients present node metadata. If a match takes place, the relevant routing
configuration is made available to those proxies. For each metadataFilter in this list, if its filterMatchCriteria is
set to MATCH_ANY, at least one of the filterLabels must match the corresponding label provided in the metadata. If its
filterMatchCriteria is set to MATCH_ALL, then all of its filterLabels must match with corresponding labels in the
provided metadata. metadataFilters specified here can be overridden by those specified in the UrlMap that this
ForwardingRule references. metadataFilters only applies to Loadbalancers that have their loadBalancingScheme set to
INTERNAL_SELF_MANAGED.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Name of the resource; provided by the client when the resource is created. The name must be 1-63 characters long, and
comply with RFC1035. Specifically, the name must be 1-63 characters long and match the regular expression
'[a-z]([-a-z0-9]*[a-z0-9])?' which means the first character must be a lowercase letter, and all following characters
must be a dash, lowercase letter, or digit, except the last character, which cannot be a dash.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Network</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}This field is not used for external load balancing. For INTERNAL_SELF_MANAGED load balancing, this field identifies the
network that the load balanced IP should belong to for this global forwarding rule. If this field is not specified, the
default network will be used.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Port<wbr>Range</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}This field is used along with the target field for TargetHttpProxy, TargetHttpsProxy, TargetSslProxy, TargetTcpProxy,
TargetVpnGateway, TargetPool, TargetInstance. Applicable only when IPProtocol is TCP, UDP, or SCTP, only packets
addressed to ports in the specified range will be forwarded to target. Forwarding rules with the same [IPAddress,
IPProtocol] pair must have disjoint port ranges. Some types of forwarding target have constraints on the acceptable
ports: * TargetHttpProxy: 80, 8080 * TargetHttpsProxy: 443 * TargetTcpProxy: 25, 43, 110, 143, 195, 443, 465, 587, 700,
993, 995, 1883, 5222 * TargetSslProxy: 25, 43, 110, 143, 195, 443, 465, 587, 700, 993, 995, 1883, 5222 *
TargetVpnGateway: 500, 4500
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Project</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Target</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The URL of the target resource to receive the matched traffic. The forwarded traffic must be of a type appropriate to
the target object. For INTERNAL_SELF_MANAGED load balancing, only HTTP and HTTPS targets are valid.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}An optional description of this resource. Provide this property when you create the resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ip<wbr>Address</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The IP address that this forwarding rule is serving on behalf of. Addresses are restricted based on the forwarding
rule's load balancing scheme (EXTERNAL or INTERNAL) and scope (global or regional). When the load balancing scheme is
EXTERNAL, for global forwarding rules, the address must be a global IP, and for regional forwarding rules, the address
must live in the same region as the forwarding rule. If this field is empty, an ephemeral IPv4 address from the same
scope (global or regional) will be assigned. A regional forwarding rule supports IPv4 only. A global forwarding rule
supports either IPv4 or IPv6. When the load balancing scheme is INTERNAL, this can only be an RFC 1918 IP address
belonging to the network/subnet configured for the forwarding rule. By default, if this field is empty, an ephemeral
internal IP address will be automatically allocated from the IP range of the subnet or network configured for this
forwarding rule. An address must be specified by a literal IP address. ~> **NOTE**: While the API allows you to specify
various resource paths for an address resource instead, Terraform requires this to specifically be an IP address to
avoid needing to fetching the IP address from resource paths on refresh or unnecessary diffs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ip<wbr>Protocol</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The IP protocol to which this rule applies. Valid options are TCP, UDP, ESP, AH, SCTP or ICMP. When the load balancing
scheme is INTERNAL_SELF_MANAGED, only TCP is valid.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ip<wbr>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The IP Version that will be used by this global forwarding rule. Valid options are IPV4 or IPV6.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: string}?</span>
    </dt>
    <dd>{{% md %}}Labels to apply to this forwarding rule. A list of key->value pairs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>load<wbr>Balancing<wbr>Scheme</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}This signifies what the GlobalForwardingRule will be used for. The value of INTERNAL_SELF_MANAGED means that this will
be used for Internal Global HTTP(S) LB. The value of EXTERNAL means that this will be used for External Global Load
Balancing (HTTP(S) LB, External TCP/UDP LB, SSL Proxy) NOTE: Currently global forwarding rules cannot be used for
INTERNAL load balancing.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>metadata<wbr>Filters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#globalforwardingrulemetadatafilter">Global<wbr>Forwarding<wbr>Rule<wbr>Metadata<wbr>Filter[]?</a></span>
    </dt>
    <dd>{{% md %}}Opaque filter criteria used by Loadbalancer to restrict routing configuration to a limited set xDS compliant clients. In
their xDS requests to Loadbalancer, xDS clients present node metadata. If a match takes place, the relevant routing
configuration is made available to those proxies. For each metadataFilter in this list, if its filterMatchCriteria is
set to MATCH_ANY, at least one of the filterLabels must match the corresponding label provided in the metadata. If its
filterMatchCriteria is set to MATCH_ALL, then all of its filterLabels must match with corresponding labels in the
provided metadata. metadataFilters specified here can be overridden by those specified in the UrlMap that this
ForwardingRule references. metadataFilters only applies to Loadbalancers that have their loadBalancingScheme set to
INTERNAL_SELF_MANAGED.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Name of the resource; provided by the client when the resource is created. The name must be 1-63 characters long, and
comply with RFC1035. Specifically, the name must be 1-63 characters long and match the regular expression
'[a-z]([-a-z0-9]*[a-z0-9])?' which means the first character must be a lowercase letter, and all following characters
must be a dash, lowercase letter, or digit, except the last character, which cannot be a dash.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>network</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}This field is not used for external load balancing. For INTERNAL_SELF_MANAGED load balancing, this field identifies the
network that the load balanced IP should belong to for this global forwarding rule. If this field is not specified, the
default network will be used.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>port<wbr>Range</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}This field is used along with the target field for TargetHttpProxy, TargetHttpsProxy, TargetSslProxy, TargetTcpProxy,
TargetVpnGateway, TargetPool, TargetInstance. Applicable only when IPProtocol is TCP, UDP, or SCTP, only packets
addressed to ports in the specified range will be forwarded to target. Forwarding rules with the same [IPAddress,
IPProtocol] pair must have disjoint port ranges. Some types of forwarding target have constraints on the acceptable
ports: * TargetHttpProxy: 80, 8080 * TargetHttpsProxy: 443 * TargetTcpProxy: 25, 43, 110, 143, 195, 443, 465, 587, 700,
993, 995, 1883, 5222 * TargetSslProxy: 25, 43, 110, 143, 195, 443, 465, 587, 700, 993, 995, 1883, 5222 *
TargetVpnGateway: 500, 4500
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>project</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>target</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The URL of the target resource to receive the matched traffic. The forwarded traffic must be of a type appropriate to
the target object. For INTERNAL_SELF_MANAGED load balancing, only HTTP and HTTPS targets are valid.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}An optional description of this resource. Provide this property when you create the resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ip_<wbr>address</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The IP address that this forwarding rule is serving on behalf of. Addresses are restricted based on the forwarding
rule's load balancing scheme (EXTERNAL or INTERNAL) and scope (global or regional). When the load balancing scheme is
EXTERNAL, for global forwarding rules, the address must be a global IP, and for regional forwarding rules, the address
must live in the same region as the forwarding rule. If this field is empty, an ephemeral IPv4 address from the same
scope (global or regional) will be assigned. A regional forwarding rule supports IPv4 only. A global forwarding rule
supports either IPv4 or IPv6. When the load balancing scheme is INTERNAL, this can only be an RFC 1918 IP address
belonging to the network/subnet configured for the forwarding rule. By default, if this field is empty, an ephemeral
internal IP address will be automatically allocated from the IP range of the subnet or network configured for this
forwarding rule. An address must be specified by a literal IP address. ~> **NOTE**: While the API allows you to specify
various resource paths for an address resource instead, Terraform requires this to specifically be an IP address to
avoid needing to fetching the IP address from resource paths on refresh or unnecessary diffs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ip_<wbr>protocol</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The IP protocol to which this rule applies. Valid options are TCP, UDP, ESP, AH, SCTP or ICMP. When the load balancing
scheme is INTERNAL_SELF_MANAGED, only TCP is valid.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ip_<wbr>version</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The IP Version that will be used by this global forwarding rule. Valid options are IPV4 or IPV6.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, str]</span>
    </dt>
    <dd>{{% md %}}Labels to apply to this forwarding rule. A list of key->value pairs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>load_<wbr>balancing_<wbr>scheme</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}This signifies what the GlobalForwardingRule will be used for. The value of INTERNAL_SELF_MANAGED means that this will
be used for Internal Global HTTP(S) LB. The value of EXTERNAL means that this will be used for External Global Load
Balancing (HTTP(S) LB, External TCP/UDP LB, SSL Proxy) NOTE: Currently global forwarding rules cannot be used for
INTERNAL load balancing.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>metadata_<wbr>filters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#globalforwardingrulemetadatafilter">List[Global<wbr>Forwarding<wbr>Rule<wbr>Metadata<wbr>Filter]</a></span>
    </dt>
    <dd>{{% md %}}Opaque filter criteria used by Loadbalancer to restrict routing configuration to a limited set xDS compliant clients. In
their xDS requests to Loadbalancer, xDS clients present node metadata. If a match takes place, the relevant routing
configuration is made available to those proxies. For each metadataFilter in this list, if its filterMatchCriteria is
set to MATCH_ANY, at least one of the filterLabels must match the corresponding label provided in the metadata. If its
filterMatchCriteria is set to MATCH_ALL, then all of its filterLabels must match with corresponding labels in the
provided metadata. metadataFilters specified here can be overridden by those specified in the UrlMap that this
ForwardingRule references. metadataFilters only applies to Loadbalancers that have their loadBalancingScheme set to
INTERNAL_SELF_MANAGED.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Name of the resource; provided by the client when the resource is created. The name must be 1-63 characters long, and
comply with RFC1035. Specifically, the name must be 1-63 characters long and match the regular expression
'[a-z]([-a-z0-9]*[a-z0-9])?' which means the first character must be a lowercase letter, and all following characters
must be a dash, lowercase letter, or digit, except the last character, which cannot be a dash.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>network</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}This field is not used for external load balancing. For INTERNAL_SELF_MANAGED load balancing, this field identifies the
network that the load balanced IP should belong to for this global forwarding rule. If this field is not specified, the
default network will be used.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>port_<wbr>range</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}This field is used along with the target field for TargetHttpProxy, TargetHttpsProxy, TargetSslProxy, TargetTcpProxy,
TargetVpnGateway, TargetPool, TargetInstance. Applicable only when IPProtocol is TCP, UDP, or SCTP, only packets
addressed to ports in the specified range will be forwarded to target. Forwarding rules with the same [IPAddress,
IPProtocol] pair must have disjoint port ranges. Some types of forwarding target have constraints on the acceptable
ports: * TargetHttpProxy: 80, 8080 * TargetHttpsProxy: 443 * TargetTcpProxy: 25, 43, 110, 143, 195, 443, 465, 587, 700,
993, 995, 1883, 5222 * TargetSslProxy: 25, 43, 110, 143, 195, 443, 465, 587, 700, 993, 995, 1883, 5222 *
TargetVpnGateway: 500, 4500
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>project</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>target</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The URL of the target resource to receive the matched traffic. The forwarded traffic must be of a type appropriate to
the target object. For INTERNAL_SELF_MANAGED load balancing, only HTTP and HTTPS targets are valid.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}







## GlobalForwardingRule Output Properties

The following output properties are available:




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}An optional description of this resource. Provide this property when you create the resource.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Ip<wbr>Address</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The IP address that this forwarding rule is serving on behalf of. Addresses are restricted based on the forwarding
rule's load balancing scheme (EXTERNAL or INTERNAL) and scope (global or regional). When the load balancing scheme is
EXTERNAL, for global forwarding rules, the address must be a global IP, and for regional forwarding rules, the address
must live in the same region as the forwarding rule. If this field is empty, an ephemeral IPv4 address from the same
scope (global or regional) will be assigned. A regional forwarding rule supports IPv4 only. A global forwarding rule
supports either IPv4 or IPv6. When the load balancing scheme is INTERNAL, this can only be an RFC 1918 IP address
belonging to the network/subnet configured for the forwarding rule. By default, if this field is empty, an ephemeral
internal IP address will be automatically allocated from the IP range of the subnet or network configured for this
forwarding rule. An address must be specified by a literal IP address. ~> **NOTE**: While the API allows you to specify
various resource paths for an address resource instead, Terraform requires this to specifically be an IP address to
avoid needing to fetching the IP address from resource paths on refresh or unnecessary diffs.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Ip<wbr>Protocol</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The IP protocol to which this rule applies. Valid options are TCP, UDP, ESP, AH, SCTP or ICMP. When the load balancing
scheme is INTERNAL_SELF_MANAGED, only TCP is valid.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Ip<wbr>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The IP Version that will be used by this global forwarding rule. Valid options are IPV4 or IPV6.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Label<wbr>Fingerprint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The fingerprint used for optimistic locking of this resource. Used internally during updates.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary<string, string>?</span>
    </dt>
    <dd>{{% md %}}Labels to apply to this forwarding rule. A list of key->value pairs.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Load<wbr>Balancing<wbr>Scheme</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}This signifies what the GlobalForwardingRule will be used for. The value of INTERNAL_SELF_MANAGED means that this will
be used for Internal Global HTTP(S) LB. The value of EXTERNAL means that this will be used for External Global Load
Balancing (HTTP(S) LB, External TCP/UDP LB, SSL Proxy) NOTE: Currently global forwarding rules cannot be used for
INTERNAL load balancing.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Metadata<wbr>Filters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#globalforwardingrulemetadatafilter">List&lt;Global<wbr>Forwarding<wbr>Rule<wbr>Metadata<wbr>Filter&gt;?</a></span>
    </dt>
    <dd>{{% md %}}Opaque filter criteria used by Loadbalancer to restrict routing configuration to a limited set xDS compliant clients. In
their xDS requests to Loadbalancer, xDS clients present node metadata. If a match takes place, the relevant routing
configuration is made available to those proxies. For each metadataFilter in this list, if its filterMatchCriteria is
set to MATCH_ANY, at least one of the filterLabels must match the corresponding label provided in the metadata. If its
filterMatchCriteria is set to MATCH_ALL, then all of its filterLabels must match with corresponding labels in the
provided metadata. metadataFilters specified here can be overridden by those specified in the UrlMap that this
ForwardingRule references. metadataFilters only applies to Loadbalancers that have their loadBalancingScheme set to
INTERNAL_SELF_MANAGED.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Name of the resource; provided by the client when the resource is created. The name must be 1-63 characters long, and
comply with RFC1035. Specifically, the name must be 1-63 characters long and match the regular expression
'[a-z]([-a-z0-9]*[a-z0-9])?' which means the first character must be a lowercase letter, and all following characters
must be a dash, lowercase letter, or digit, except the last character, which cannot be a dash.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Network</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}This field is not used for external load balancing. For INTERNAL_SELF_MANAGED load balancing, this field identifies the
network that the load balanced IP should belong to for this global forwarding rule. If this field is not specified, the
default network will be used.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Port<wbr>Range</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}This field is used along with the target field for TargetHttpProxy, TargetHttpsProxy, TargetSslProxy, TargetTcpProxy,
TargetVpnGateway, TargetPool, TargetInstance. Applicable only when IPProtocol is TCP, UDP, or SCTP, only packets
addressed to ports in the specified range will be forwarded to target. Forwarding rules with the same [IPAddress,
IPProtocol] pair must have disjoint port ranges. Some types of forwarding target have constraints on the acceptable
ports: * TargetHttpProxy: 80, 8080 * TargetHttpsProxy: 443 * TargetTcpProxy: 25, 43, 110, 143, 195, 443, 465, 587, 700,
993, 995, 1883, 5222 * TargetSslProxy: 25, 43, 110, 143, 195, 443, 465, 587, 700, 993, 995, 1883, 5222 *
TargetVpnGateway: 500, 4500
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Project</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Self<wbr>Link</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The URI of the created resource.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Target</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The URL of the target resource to receive the matched traffic. The forwarded traffic must be of a type appropriate to
the target object. For INTERNAL_SELF_MANAGED load balancing, only HTTP and HTTPS targets are valid.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}An optional description of this resource. Provide this property when you create the resource.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Ip<wbr>Address</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The IP address that this forwarding rule is serving on behalf of. Addresses are restricted based on the forwarding
rule's load balancing scheme (EXTERNAL or INTERNAL) and scope (global or regional). When the load balancing scheme is
EXTERNAL, for global forwarding rules, the address must be a global IP, and for regional forwarding rules, the address
must live in the same region as the forwarding rule. If this field is empty, an ephemeral IPv4 address from the same
scope (global or regional) will be assigned. A regional forwarding rule supports IPv4 only. A global forwarding rule
supports either IPv4 or IPv6. When the load balancing scheme is INTERNAL, this can only be an RFC 1918 IP address
belonging to the network/subnet configured for the forwarding rule. By default, if this field is empty, an ephemeral
internal IP address will be automatically allocated from the IP range of the subnet or network configured for this
forwarding rule. An address must be specified by a literal IP address. ~> **NOTE**: While the API allows you to specify
various resource paths for an address resource instead, Terraform requires this to specifically be an IP address to
avoid needing to fetching the IP address from resource paths on refresh or unnecessary diffs.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Ip<wbr>Protocol</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The IP protocol to which this rule applies. Valid options are TCP, UDP, ESP, AH, SCTP or ICMP. When the load balancing
scheme is INTERNAL_SELF_MANAGED, only TCP is valid.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Ip<wbr>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The IP Version that will be used by this global forwarding rule. Valid options are IPV4 or IPV6.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Label<wbr>Fingerprint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The fingerprint used for optimistic locking of this resource. Used internally during updates.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]string</span>
    </dt>
    <dd>{{% md %}}Labels to apply to this forwarding rule. A list of key->value pairs.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Load<wbr>Balancing<wbr>Scheme</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}This signifies what the GlobalForwardingRule will be used for. The value of INTERNAL_SELF_MANAGED means that this will
be used for Internal Global HTTP(S) LB. The value of EXTERNAL means that this will be used for External Global Load
Balancing (HTTP(S) LB, External TCP/UDP LB, SSL Proxy) NOTE: Currently global forwarding rules cannot be used for
INTERNAL load balancing.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Metadata<wbr>Filters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#globalforwardingrulemetadatafilter">[]Global<wbr>Forwarding<wbr>Rule<wbr>Metadata<wbr>Filter</a></span>
    </dt>
    <dd>{{% md %}}Opaque filter criteria used by Loadbalancer to restrict routing configuration to a limited set xDS compliant clients. In
their xDS requests to Loadbalancer, xDS clients present node metadata. If a match takes place, the relevant routing
configuration is made available to those proxies. For each metadataFilter in this list, if its filterMatchCriteria is
set to MATCH_ANY, at least one of the filterLabels must match the corresponding label provided in the metadata. If its
filterMatchCriteria is set to MATCH_ALL, then all of its filterLabels must match with corresponding labels in the
provided metadata. metadataFilters specified here can be overridden by those specified in the UrlMap that this
ForwardingRule references. metadataFilters only applies to Loadbalancers that have their loadBalancingScheme set to
INTERNAL_SELF_MANAGED.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Name of the resource; provided by the client when the resource is created. The name must be 1-63 characters long, and
comply with RFC1035. Specifically, the name must be 1-63 characters long and match the regular expression
'[a-z]([-a-z0-9]*[a-z0-9])?' which means the first character must be a lowercase letter, and all following characters
must be a dash, lowercase letter, or digit, except the last character, which cannot be a dash.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Network</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}This field is not used for external load balancing. For INTERNAL_SELF_MANAGED load balancing, this field identifies the
network that the load balanced IP should belong to for this global forwarding rule. If this field is not specified, the
default network will be used.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Port<wbr>Range</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}This field is used along with the target field for TargetHttpProxy, TargetHttpsProxy, TargetSslProxy, TargetTcpProxy,
TargetVpnGateway, TargetPool, TargetInstance. Applicable only when IPProtocol is TCP, UDP, or SCTP, only packets
addressed to ports in the specified range will be forwarded to target. Forwarding rules with the same [IPAddress,
IPProtocol] pair must have disjoint port ranges. Some types of forwarding target have constraints on the acceptable
ports: * TargetHttpProxy: 80, 8080 * TargetHttpsProxy: 443 * TargetTcpProxy: 25, 43, 110, 143, 195, 443, 465, 587, 700,
993, 995, 1883, 5222 * TargetSslProxy: 25, 43, 110, 143, 195, 443, 465, 587, 700, 993, 995, 1883, 5222 *
TargetVpnGateway: 500, 4500
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Project</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Self<wbr>Link</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The URI of the created resource.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Target</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The URL of the target resource to receive the matched traffic. The forwarded traffic must be of a type appropriate to
the target object. For INTERNAL_SELF_MANAGED load balancing, only HTTP and HTTPS targets are valid.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}An optional description of this resource. Provide this property when you create the resource.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>ip<wbr>Address</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The IP address that this forwarding rule is serving on behalf of. Addresses are restricted based on the forwarding
rule's load balancing scheme (EXTERNAL or INTERNAL) and scope (global or regional). When the load balancing scheme is
EXTERNAL, for global forwarding rules, the address must be a global IP, and for regional forwarding rules, the address
must live in the same region as the forwarding rule. If this field is empty, an ephemeral IPv4 address from the same
scope (global or regional) will be assigned. A regional forwarding rule supports IPv4 only. A global forwarding rule
supports either IPv4 or IPv6. When the load balancing scheme is INTERNAL, this can only be an RFC 1918 IP address
belonging to the network/subnet configured for the forwarding rule. By default, if this field is empty, an ephemeral
internal IP address will be automatically allocated from the IP range of the subnet or network configured for this
forwarding rule. An address must be specified by a literal IP address. ~> **NOTE**: While the API allows you to specify
various resource paths for an address resource instead, Terraform requires this to specifically be an IP address to
avoid needing to fetching the IP address from resource paths on refresh or unnecessary diffs.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>ip<wbr>Protocol</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The IP protocol to which this rule applies. Valid options are TCP, UDP, ESP, AH, SCTP or ICMP. When the load balancing
scheme is INTERNAL_SELF_MANAGED, only TCP is valid.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>ip<wbr>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The IP Version that will be used by this global forwarding rule. Valid options are IPV4 or IPV6.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>label<wbr>Fingerprint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The fingerprint used for optimistic locking of this resource. Used internally during updates.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: string}?</span>
    </dt>
    <dd>{{% md %}}Labels to apply to this forwarding rule. A list of key->value pairs.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>load<wbr>Balancing<wbr>Scheme</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}This signifies what the GlobalForwardingRule will be used for. The value of INTERNAL_SELF_MANAGED means that this will
be used for Internal Global HTTP(S) LB. The value of EXTERNAL means that this will be used for External Global Load
Balancing (HTTP(S) LB, External TCP/UDP LB, SSL Proxy) NOTE: Currently global forwarding rules cannot be used for
INTERNAL load balancing.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>metadata<wbr>Filters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#globalforwardingrulemetadatafilter">Global<wbr>Forwarding<wbr>Rule<wbr>Metadata<wbr>Filter[]?</a></span>
    </dt>
    <dd>{{% md %}}Opaque filter criteria used by Loadbalancer to restrict routing configuration to a limited set xDS compliant clients. In
their xDS requests to Loadbalancer, xDS clients present node metadata. If a match takes place, the relevant routing
configuration is made available to those proxies. For each metadataFilter in this list, if its filterMatchCriteria is
set to MATCH_ANY, at least one of the filterLabels must match the corresponding label provided in the metadata. If its
filterMatchCriteria is set to MATCH_ALL, then all of its filterLabels must match with corresponding labels in the
provided metadata. metadataFilters specified here can be overridden by those specified in the UrlMap that this
ForwardingRule references. metadataFilters only applies to Loadbalancers that have their loadBalancingScheme set to
INTERNAL_SELF_MANAGED.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Name of the resource; provided by the client when the resource is created. The name must be 1-63 characters long, and
comply with RFC1035. Specifically, the name must be 1-63 characters long and match the regular expression
'[a-z]([-a-z0-9]*[a-z0-9])?' which means the first character must be a lowercase letter, and all following characters
must be a dash, lowercase letter, or digit, except the last character, which cannot be a dash.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>network</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}This field is not used for external load balancing. For INTERNAL_SELF_MANAGED load balancing, this field identifies the
network that the load balanced IP should belong to for this global forwarding rule. If this field is not specified, the
default network will be used.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>port<wbr>Range</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}This field is used along with the target field for TargetHttpProxy, TargetHttpsProxy, TargetSslProxy, TargetTcpProxy,
TargetVpnGateway, TargetPool, TargetInstance. Applicable only when IPProtocol is TCP, UDP, or SCTP, only packets
addressed to ports in the specified range will be forwarded to target. Forwarding rules with the same [IPAddress,
IPProtocol] pair must have disjoint port ranges. Some types of forwarding target have constraints on the acceptable
ports: * TargetHttpProxy: 80, 8080 * TargetHttpsProxy: 443 * TargetTcpProxy: 25, 43, 110, 143, 195, 443, 465, 587, 700,
993, 995, 1883, 5222 * TargetSslProxy: 25, 43, 110, 143, 195, 443, 465, 587, 700, 993, 995, 1883, 5222 *
TargetVpnGateway: 500, 4500
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>project</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>self<wbr>Link</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The URI of the created resource.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>target</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The URL of the target resource to receive the matched traffic. The forwarded traffic must be of a type appropriate to
the target object. For INTERNAL_SELF_MANAGED load balancing, only HTTP and HTTPS targets are valid.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}An optional description of this resource. Provide this property when you create the resource.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>ip_<wbr>address</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The IP address that this forwarding rule is serving on behalf of. Addresses are restricted based on the forwarding
rule's load balancing scheme (EXTERNAL or INTERNAL) and scope (global or regional). When the load balancing scheme is
EXTERNAL, for global forwarding rules, the address must be a global IP, and for regional forwarding rules, the address
must live in the same region as the forwarding rule. If this field is empty, an ephemeral IPv4 address from the same
scope (global or regional) will be assigned. A regional forwarding rule supports IPv4 only. A global forwarding rule
supports either IPv4 or IPv6. When the load balancing scheme is INTERNAL, this can only be an RFC 1918 IP address
belonging to the network/subnet configured for the forwarding rule. By default, if this field is empty, an ephemeral
internal IP address will be automatically allocated from the IP range of the subnet or network configured for this
forwarding rule. An address must be specified by a literal IP address. ~> **NOTE**: While the API allows you to specify
various resource paths for an address resource instead, Terraform requires this to specifically be an IP address to
avoid needing to fetching the IP address from resource paths on refresh or unnecessary diffs.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>ip_<wbr>protocol</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The IP protocol to which this rule applies. Valid options are TCP, UDP, ESP, AH, SCTP or ICMP. When the load balancing
scheme is INTERNAL_SELF_MANAGED, only TCP is valid.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>ip_<wbr>version</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The IP Version that will be used by this global forwarding rule. Valid options are IPV4 or IPV6.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>label_<wbr>fingerprint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The fingerprint used for optimistic locking of this resource. Used internally during updates.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, str]</span>
    </dt>
    <dd>{{% md %}}Labels to apply to this forwarding rule. A list of key->value pairs.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>load_<wbr>balancing_<wbr>scheme</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}This signifies what the GlobalForwardingRule will be used for. The value of INTERNAL_SELF_MANAGED means that this will
be used for Internal Global HTTP(S) LB. The value of EXTERNAL means that this will be used for External Global Load
Balancing (HTTP(S) LB, External TCP/UDP LB, SSL Proxy) NOTE: Currently global forwarding rules cannot be used for
INTERNAL load balancing.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>metadata_<wbr>filters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#globalforwardingrulemetadatafilter">List[Global<wbr>Forwarding<wbr>Rule<wbr>Metadata<wbr>Filter]</a></span>
    </dt>
    <dd>{{% md %}}Opaque filter criteria used by Loadbalancer to restrict routing configuration to a limited set xDS compliant clients. In
their xDS requests to Loadbalancer, xDS clients present node metadata. If a match takes place, the relevant routing
configuration is made available to those proxies. For each metadataFilter in this list, if its filterMatchCriteria is
set to MATCH_ANY, at least one of the filterLabels must match the corresponding label provided in the metadata. If its
filterMatchCriteria is set to MATCH_ALL, then all of its filterLabels must match with corresponding labels in the
provided metadata. metadataFilters specified here can be overridden by those specified in the UrlMap that this
ForwardingRule references. metadataFilters only applies to Loadbalancers that have their loadBalancingScheme set to
INTERNAL_SELF_MANAGED.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Name of the resource; provided by the client when the resource is created. The name must be 1-63 characters long, and
comply with RFC1035. Specifically, the name must be 1-63 characters long and match the regular expression
'[a-z]([-a-z0-9]*[a-z0-9])?' which means the first character must be a lowercase letter, and all following characters
must be a dash, lowercase letter, or digit, except the last character, which cannot be a dash.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>network</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}This field is not used for external load balancing. For INTERNAL_SELF_MANAGED load balancing, this field identifies the
network that the load balanced IP should belong to for this global forwarding rule. If this field is not specified, the
default network will be used.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>port_<wbr>range</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}This field is used along with the target field for TargetHttpProxy, TargetHttpsProxy, TargetSslProxy, TargetTcpProxy,
TargetVpnGateway, TargetPool, TargetInstance. Applicable only when IPProtocol is TCP, UDP, or SCTP, only packets
addressed to ports in the specified range will be forwarded to target. Forwarding rules with the same [IPAddress,
IPProtocol] pair must have disjoint port ranges. Some types of forwarding target have constraints on the acceptable
ports: * TargetHttpProxy: 80, 8080 * TargetHttpsProxy: 443 * TargetTcpProxy: 25, 43, 110, 143, 195, 443, 465, 587, 700,
993, 995, 1883, 5222 * TargetSslProxy: 25, 43, 110, 143, 195, 443, 465, 587, 700, 993, 995, 1883, 5222 *
TargetVpnGateway: 500, 4500
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>project</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>self_<wbr>link</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The URI of the created resource.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>target</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The URL of the target resource to receive the matched traffic. The forwarded traffic must be of a type appropriate to
the target object. For INTERNAL_SELF_MANAGED load balancing, only HTTP and HTTPS targets are valid.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}








## Look up an Existing GlobalForwardingRule Resource

Get an existing GlobalForwardingRule resource's state with the given name, ID, and optional extra properties used to qualify the lookup.

{{< chooser language "javascript,typescript,python,go,csharp  " / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">public static </span><span class="nf">get</span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">id</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#ID">Input&lt;ID&gt;</a></span><span class="p">, </span><span class="nx">state</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/gcp/compute/#GlobalForwardingRuleState">GlobalForwardingRuleState</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">CustomResourceOptions</a></span><span class="p">): </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/gcp/compute/#GlobalForwardingRule">GlobalForwardingRule</a></span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">static </span><span class="nf">get</span><span class="p">(resource_name, id, opts=None, </span>description=None<span class="p">, </span>ip_address=None<span class="p">, </span>ip_protocol=None<span class="p">, </span>ip_version=None<span class="p">, </span>label_fingerprint=None<span class="p">, </span>labels=None<span class="p">, </span>load_balancing_scheme=None<span class="p">, </span>metadata_filters=None<span class="p">, </span>name=None<span class="p">, </span>network=None<span class="p">, </span>port_range=None<span class="p">, </span>project=None<span class="p">, </span>self_link=None<span class="p">, </span>target=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>GetGlobalForwardingRule<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">id</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#IDInput">IDInput</a></span><span class="p">, </span><span class="nx">state</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-gcp/sdk/go/gcp/compute?tab=doc#GlobalForwardingRuleState">GlobalForwardingRuleState</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-gcp/sdk/go/gcp/compute?tab=doc#GlobalForwardingRule">GlobalForwardingRule</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Gcp/Pulumi.Gcp.Compute.GlobalForwardingRule.html">GlobalForwardingRule</a></span><span class="nf"> Get</span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.Input.html">Input&lt;string&gt;</a></span> <span class="nx">id<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Gcp/Pulumi.Gcp.Compute.GlobalForwardingRuleState.html">GlobalForwardingRuleState</a></span>? <span class="nx">state<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language nodejs %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>resource_name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Optional">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language csharp %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

The following state arguments are supported:



{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}An optional description of this resource. Provide this property when you create the resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ip<wbr>Address</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The IP address that this forwarding rule is serving on behalf of. Addresses are restricted based on the forwarding
rule's load balancing scheme (EXTERNAL or INTERNAL) and scope (global or regional). When the load balancing scheme is
EXTERNAL, for global forwarding rules, the address must be a global IP, and for regional forwarding rules, the address
must live in the same region as the forwarding rule. If this field is empty, an ephemeral IPv4 address from the same
scope (global or regional) will be assigned. A regional forwarding rule supports IPv4 only. A global forwarding rule
supports either IPv4 or IPv6. When the load balancing scheme is INTERNAL, this can only be an RFC 1918 IP address
belonging to the network/subnet configured for the forwarding rule. By default, if this field is empty, an ephemeral
internal IP address will be automatically allocated from the IP range of the subnet or network configured for this
forwarding rule. An address must be specified by a literal IP address. ~> **NOTE**: While the API allows you to specify
various resource paths for an address resource instead, Terraform requires this to specifically be an IP address to
avoid needing to fetching the IP address from resource paths on refresh or unnecessary diffs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ip<wbr>Protocol</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The IP protocol to which this rule applies. Valid options are TCP, UDP, ESP, AH, SCTP or ICMP. When the load balancing
scheme is INTERNAL_SELF_MANAGED, only TCP is valid.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ip<wbr>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The IP Version that will be used by this global forwarding rule. Valid options are IPV4 or IPV6.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Label<wbr>Fingerprint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The fingerprint used for optimistic locking of this resource. Used internally during updates.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary<string, string>?</span>
    </dt>
    <dd>{{% md %}}Labels to apply to this forwarding rule. A list of key->value pairs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Load<wbr>Balancing<wbr>Scheme</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}This signifies what the GlobalForwardingRule will be used for. The value of INTERNAL_SELF_MANAGED means that this will
be used for Internal Global HTTP(S) LB. The value of EXTERNAL means that this will be used for External Global Load
Balancing (HTTP(S) LB, External TCP/UDP LB, SSL Proxy) NOTE: Currently global forwarding rules cannot be used for
INTERNAL load balancing.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Metadata<wbr>Filters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#globalforwardingrulemetadatafilter">List&lt;Global<wbr>Forwarding<wbr>Rule<wbr>Metadata<wbr>Filter<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}Opaque filter criteria used by Loadbalancer to restrict routing configuration to a limited set xDS compliant clients. In
their xDS requests to Loadbalancer, xDS clients present node metadata. If a match takes place, the relevant routing
configuration is made available to those proxies. For each metadataFilter in this list, if its filterMatchCriteria is
set to MATCH_ANY, at least one of the filterLabels must match the corresponding label provided in the metadata. If its
filterMatchCriteria is set to MATCH_ALL, then all of its filterLabels must match with corresponding labels in the
provided metadata. metadataFilters specified here can be overridden by those specified in the UrlMap that this
ForwardingRule references. metadataFilters only applies to Loadbalancers that have their loadBalancingScheme set to
INTERNAL_SELF_MANAGED.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Name of the resource; provided by the client when the resource is created. The name must be 1-63 characters long, and
comply with RFC1035. Specifically, the name must be 1-63 characters long and match the regular expression
'[a-z]([-a-z0-9]*[a-z0-9])?' which means the first character must be a lowercase letter, and all following characters
must be a dash, lowercase letter, or digit, except the last character, which cannot be a dash.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Network</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}This field is not used for external load balancing. For INTERNAL_SELF_MANAGED load balancing, this field identifies the
network that the load balanced IP should belong to for this global forwarding rule. If this field is not specified, the
default network will be used.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Port<wbr>Range</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}This field is used along with the target field for TargetHttpProxy, TargetHttpsProxy, TargetSslProxy, TargetTcpProxy,
TargetVpnGateway, TargetPool, TargetInstance. Applicable only when IPProtocol is TCP, UDP, or SCTP, only packets
addressed to ports in the specified range will be forwarded to target. Forwarding rules with the same [IPAddress,
IPProtocol] pair must have disjoint port ranges. Some types of forwarding target have constraints on the acceptable
ports: * TargetHttpProxy: 80, 8080 * TargetHttpsProxy: 443 * TargetTcpProxy: 25, 43, 110, 143, 195, 443, 465, 587, 700,
993, 995, 1883, 5222 * TargetSslProxy: 25, 43, 110, 143, 195, 443, 465, 587, 700, 993, 995, 1883, 5222 *
TargetVpnGateway: 500, 4500
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Project</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Self<wbr>Link</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The URI of the created resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Target</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The URL of the target resource to receive the matched traffic. The forwarded traffic must be of a type appropriate to
the target object. For INTERNAL_SELF_MANAGED load balancing, only HTTP and HTTPS targets are valid.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}An optional description of this resource. Provide this property when you create the resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ip<wbr>Address</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The IP address that this forwarding rule is serving on behalf of. Addresses are restricted based on the forwarding
rule's load balancing scheme (EXTERNAL or INTERNAL) and scope (global or regional). When the load balancing scheme is
EXTERNAL, for global forwarding rules, the address must be a global IP, and for regional forwarding rules, the address
must live in the same region as the forwarding rule. If this field is empty, an ephemeral IPv4 address from the same
scope (global or regional) will be assigned. A regional forwarding rule supports IPv4 only. A global forwarding rule
supports either IPv4 or IPv6. When the load balancing scheme is INTERNAL, this can only be an RFC 1918 IP address
belonging to the network/subnet configured for the forwarding rule. By default, if this field is empty, an ephemeral
internal IP address will be automatically allocated from the IP range of the subnet or network configured for this
forwarding rule. An address must be specified by a literal IP address. ~> **NOTE**: While the API allows you to specify
various resource paths for an address resource instead, Terraform requires this to specifically be an IP address to
avoid needing to fetching the IP address from resource paths on refresh or unnecessary diffs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ip<wbr>Protocol</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The IP protocol to which this rule applies. Valid options are TCP, UDP, ESP, AH, SCTP or ICMP. When the load balancing
scheme is INTERNAL_SELF_MANAGED, only TCP is valid.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Ip<wbr>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The IP Version that will be used by this global forwarding rule. Valid options are IPV4 or IPV6.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Label<wbr>Fingerprint</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The fingerprint used for optimistic locking of this resource. Used internally during updates.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]string</span>
    </dt>
    <dd>{{% md %}}Labels to apply to this forwarding rule. A list of key->value pairs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Load<wbr>Balancing<wbr>Scheme</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}This signifies what the GlobalForwardingRule will be used for. The value of INTERNAL_SELF_MANAGED means that this will
be used for Internal Global HTTP(S) LB. The value of EXTERNAL means that this will be used for External Global Load
Balancing (HTTP(S) LB, External TCP/UDP LB, SSL Proxy) NOTE: Currently global forwarding rules cannot be used for
INTERNAL load balancing.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Metadata<wbr>Filters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#globalforwardingrulemetadatafilter">[]Global<wbr>Forwarding<wbr>Rule<wbr>Metadata<wbr>Filter</a></span>
    </dt>
    <dd>{{% md %}}Opaque filter criteria used by Loadbalancer to restrict routing configuration to a limited set xDS compliant clients. In
their xDS requests to Loadbalancer, xDS clients present node metadata. If a match takes place, the relevant routing
configuration is made available to those proxies. For each metadataFilter in this list, if its filterMatchCriteria is
set to MATCH_ANY, at least one of the filterLabels must match the corresponding label provided in the metadata. If its
filterMatchCriteria is set to MATCH_ALL, then all of its filterLabels must match with corresponding labels in the
provided metadata. metadataFilters specified here can be overridden by those specified in the UrlMap that this
ForwardingRule references. metadataFilters only applies to Loadbalancers that have their loadBalancingScheme set to
INTERNAL_SELF_MANAGED.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Name of the resource; provided by the client when the resource is created. The name must be 1-63 characters long, and
comply with RFC1035. Specifically, the name must be 1-63 characters long and match the regular expression
'[a-z]([-a-z0-9]*[a-z0-9])?' which means the first character must be a lowercase letter, and all following characters
must be a dash, lowercase letter, or digit, except the last character, which cannot be a dash.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Network</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}This field is not used for external load balancing. For INTERNAL_SELF_MANAGED load balancing, this field identifies the
network that the load balanced IP should belong to for this global forwarding rule. If this field is not specified, the
default network will be used.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Port<wbr>Range</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}This field is used along with the target field for TargetHttpProxy, TargetHttpsProxy, TargetSslProxy, TargetTcpProxy,
TargetVpnGateway, TargetPool, TargetInstance. Applicable only when IPProtocol is TCP, UDP, or SCTP, only packets
addressed to ports in the specified range will be forwarded to target. Forwarding rules with the same [IPAddress,
IPProtocol] pair must have disjoint port ranges. Some types of forwarding target have constraints on the acceptable
ports: * TargetHttpProxy: 80, 8080 * TargetHttpsProxy: 443 * TargetTcpProxy: 25, 43, 110, 143, 195, 443, 465, 587, 700,
993, 995, 1883, 5222 * TargetSslProxy: 25, 43, 110, 143, 195, 443, 465, 587, 700, 993, 995, 1883, 5222 *
TargetVpnGateway: 500, 4500
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Project</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Self<wbr>Link</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The URI of the created resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Target</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The URL of the target resource to receive the matched traffic. The forwarded traffic must be of a type appropriate to
the target object. For INTERNAL_SELF_MANAGED load balancing, only HTTP and HTTPS targets are valid.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}An optional description of this resource. Provide this property when you create the resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ip<wbr>Address</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The IP address that this forwarding rule is serving on behalf of. Addresses are restricted based on the forwarding
rule's load balancing scheme (EXTERNAL or INTERNAL) and scope (global or regional). When the load balancing scheme is
EXTERNAL, for global forwarding rules, the address must be a global IP, and for regional forwarding rules, the address
must live in the same region as the forwarding rule. If this field is empty, an ephemeral IPv4 address from the same
scope (global or regional) will be assigned. A regional forwarding rule supports IPv4 only. A global forwarding rule
supports either IPv4 or IPv6. When the load balancing scheme is INTERNAL, this can only be an RFC 1918 IP address
belonging to the network/subnet configured for the forwarding rule. By default, if this field is empty, an ephemeral
internal IP address will be automatically allocated from the IP range of the subnet or network configured for this
forwarding rule. An address must be specified by a literal IP address. ~> **NOTE**: While the API allows you to specify
various resource paths for an address resource instead, Terraform requires this to specifically be an IP address to
avoid needing to fetching the IP address from resource paths on refresh or unnecessary diffs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ip<wbr>Protocol</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The IP protocol to which this rule applies. Valid options are TCP, UDP, ESP, AH, SCTP or ICMP. When the load balancing
scheme is INTERNAL_SELF_MANAGED, only TCP is valid.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ip<wbr>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The IP Version that will be used by this global forwarding rule. Valid options are IPV4 or IPV6.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>label<wbr>Fingerprint</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The fingerprint used for optimistic locking of this resource. Used internally during updates.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: string}?</span>
    </dt>
    <dd>{{% md %}}Labels to apply to this forwarding rule. A list of key->value pairs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>load<wbr>Balancing<wbr>Scheme</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}This signifies what the GlobalForwardingRule will be used for. The value of INTERNAL_SELF_MANAGED means that this will
be used for Internal Global HTTP(S) LB. The value of EXTERNAL means that this will be used for External Global Load
Balancing (HTTP(S) LB, External TCP/UDP LB, SSL Proxy) NOTE: Currently global forwarding rules cannot be used for
INTERNAL load balancing.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>metadata<wbr>Filters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#globalforwardingrulemetadatafilter">Global<wbr>Forwarding<wbr>Rule<wbr>Metadata<wbr>Filter[]?</a></span>
    </dt>
    <dd>{{% md %}}Opaque filter criteria used by Loadbalancer to restrict routing configuration to a limited set xDS compliant clients. In
their xDS requests to Loadbalancer, xDS clients present node metadata. If a match takes place, the relevant routing
configuration is made available to those proxies. For each metadataFilter in this list, if its filterMatchCriteria is
set to MATCH_ANY, at least one of the filterLabels must match the corresponding label provided in the metadata. If its
filterMatchCriteria is set to MATCH_ALL, then all of its filterLabels must match with corresponding labels in the
provided metadata. metadataFilters specified here can be overridden by those specified in the UrlMap that this
ForwardingRule references. metadataFilters only applies to Loadbalancers that have their loadBalancingScheme set to
INTERNAL_SELF_MANAGED.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Name of the resource; provided by the client when the resource is created. The name must be 1-63 characters long, and
comply with RFC1035. Specifically, the name must be 1-63 characters long and match the regular expression
'[a-z]([-a-z0-9]*[a-z0-9])?' which means the first character must be a lowercase letter, and all following characters
must be a dash, lowercase letter, or digit, except the last character, which cannot be a dash.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>network</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}This field is not used for external load balancing. For INTERNAL_SELF_MANAGED load balancing, this field identifies the
network that the load balanced IP should belong to for this global forwarding rule. If this field is not specified, the
default network will be used.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>port<wbr>Range</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}This field is used along with the target field for TargetHttpProxy, TargetHttpsProxy, TargetSslProxy, TargetTcpProxy,
TargetVpnGateway, TargetPool, TargetInstance. Applicable only when IPProtocol is TCP, UDP, or SCTP, only packets
addressed to ports in the specified range will be forwarded to target. Forwarding rules with the same [IPAddress,
IPProtocol] pair must have disjoint port ranges. Some types of forwarding target have constraints on the acceptable
ports: * TargetHttpProxy: 80, 8080 * TargetHttpsProxy: 443 * TargetTcpProxy: 25, 43, 110, 143, 195, 443, 465, 587, 700,
993, 995, 1883, 5222 * TargetSslProxy: 25, 43, 110, 143, 195, 443, 465, 587, 700, 993, 995, 1883, 5222 *
TargetVpnGateway: 500, 4500
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>project</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>self<wbr>Link</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The URI of the created resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>target</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The URL of the target resource to receive the matched traffic. The forwarded traffic must be of a type appropriate to
the target object. For INTERNAL_SELF_MANAGED load balancing, only HTTP and HTTPS targets are valid.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}An optional description of this resource. Provide this property when you create the resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ip_<wbr>address</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The IP address that this forwarding rule is serving on behalf of. Addresses are restricted based on the forwarding
rule's load balancing scheme (EXTERNAL or INTERNAL) and scope (global or regional). When the load balancing scheme is
EXTERNAL, for global forwarding rules, the address must be a global IP, and for regional forwarding rules, the address
must live in the same region as the forwarding rule. If this field is empty, an ephemeral IPv4 address from the same
scope (global or regional) will be assigned. A regional forwarding rule supports IPv4 only. A global forwarding rule
supports either IPv4 or IPv6. When the load balancing scheme is INTERNAL, this can only be an RFC 1918 IP address
belonging to the network/subnet configured for the forwarding rule. By default, if this field is empty, an ephemeral
internal IP address will be automatically allocated from the IP range of the subnet or network configured for this
forwarding rule. An address must be specified by a literal IP address. ~> **NOTE**: While the API allows you to specify
various resource paths for an address resource instead, Terraform requires this to specifically be an IP address to
avoid needing to fetching the IP address from resource paths on refresh or unnecessary diffs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ip_<wbr>protocol</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The IP protocol to which this rule applies. Valid options are TCP, UDP, ESP, AH, SCTP or ICMP. When the load balancing
scheme is INTERNAL_SELF_MANAGED, only TCP is valid.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>ip_<wbr>version</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The IP Version that will be used by this global forwarding rule. Valid options are IPV4 or IPV6.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>label_<wbr>fingerprint</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The fingerprint used for optimistic locking of this resource. Used internally during updates.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, str]</span>
    </dt>
    <dd>{{% md %}}Labels to apply to this forwarding rule. A list of key->value pairs.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>load_<wbr>balancing_<wbr>scheme</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}This signifies what the GlobalForwardingRule will be used for. The value of INTERNAL_SELF_MANAGED means that this will
be used for Internal Global HTTP(S) LB. The value of EXTERNAL means that this will be used for External Global Load
Balancing (HTTP(S) LB, External TCP/UDP LB, SSL Proxy) NOTE: Currently global forwarding rules cannot be used for
INTERNAL load balancing.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>metadata_<wbr>filters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#globalforwardingrulemetadatafilter">List[Global<wbr>Forwarding<wbr>Rule<wbr>Metadata<wbr>Filter]</a></span>
    </dt>
    <dd>{{% md %}}Opaque filter criteria used by Loadbalancer to restrict routing configuration to a limited set xDS compliant clients. In
their xDS requests to Loadbalancer, xDS clients present node metadata. If a match takes place, the relevant routing
configuration is made available to those proxies. For each metadataFilter in this list, if its filterMatchCriteria is
set to MATCH_ANY, at least one of the filterLabels must match the corresponding label provided in the metadata. If its
filterMatchCriteria is set to MATCH_ALL, then all of its filterLabels must match with corresponding labels in the
provided metadata. metadataFilters specified here can be overridden by those specified in the UrlMap that this
ForwardingRule references. metadataFilters only applies to Loadbalancers that have their loadBalancingScheme set to
INTERNAL_SELF_MANAGED.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Name of the resource; provided by the client when the resource is created. The name must be 1-63 characters long, and
comply with RFC1035. Specifically, the name must be 1-63 characters long and match the regular expression
'[a-z]([-a-z0-9]*[a-z0-9])?' which means the first character must be a lowercase letter, and all following characters
must be a dash, lowercase letter, or digit, except the last character, which cannot be a dash.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>network</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}This field is not used for external load balancing. For INTERNAL_SELF_MANAGED load balancing, this field identifies the
network that the load balanced IP should belong to for this global forwarding rule. If this field is not specified, the
default network will be used.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>port_<wbr>range</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}This field is used along with the target field for TargetHttpProxy, TargetHttpsProxy, TargetSslProxy, TargetTcpProxy,
TargetVpnGateway, TargetPool, TargetInstance. Applicable only when IPProtocol is TCP, UDP, or SCTP, only packets
addressed to ports in the specified range will be forwarded to target. Forwarding rules with the same [IPAddress,
IPProtocol] pair must have disjoint port ranges. Some types of forwarding target have constraints on the acceptable
ports: * TargetHttpProxy: 80, 8080 * TargetHttpsProxy: 443 * TargetTcpProxy: 25, 43, 110, 143, 195, 443, 465, 587, 700,
993, 995, 1883, 5222 * TargetSslProxy: 25, 43, 110, 143, 195, 443, 465, 587, 700, 993, 995, 1883, 5222 *
TargetVpnGateway: 500, 4500
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>project</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>self_<wbr>link</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The URI of the created resource.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>target</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The URL of the target resource to receive the matched traffic. The forwarded traffic must be of a type appropriate to
the target object. For INTERNAL_SELF_MANAGED load balancing, only HTTP and HTTPS targets are valid.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}










## Supporting Types

<h4>Global<wbr>Forwarding<wbr>Rule<wbr>Metadata<wbr>Filter</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/gcp/types/input/#GlobalForwardingRuleMetadataFilter">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/gcp/types/output/#GlobalForwardingRuleMetadataFilter">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-gcp/sdk/go/gcp/compute?tab=doc#GlobalForwardingRuleMetadataFilterArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-gcp/sdk/go/gcp/compute?tab=doc#GlobalForwardingRuleMetadataFilterOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Filter<wbr>Labels</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#globalforwardingrulemetadatafilterfilterlabel">List&lt;Global<wbr>Forwarding<wbr>Rule<wbr>Metadata<wbr>Filter<wbr>Filter<wbr>Label<wbr>Args&gt;</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Filter<wbr>Match<wbr>Criteria</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Filter<wbr>Labels</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#globalforwardingrulemetadatafilterfilterlabel">[]Global<wbr>Forwarding<wbr>Rule<wbr>Metadata<wbr>Filter<wbr>Filter<wbr>Label</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Filter<wbr>Match<wbr>Criteria</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>filter<wbr>Labels</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#globalforwardingrulemetadatafilterfilterlabel">Global<wbr>Forwarding<wbr>Rule<wbr>Metadata<wbr>Filter<wbr>Filter<wbr>Label[]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>filter<wbr>Match<wbr>Criteria</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>filter<wbr>Labels</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#globalforwardingrulemetadatafilterfilterlabel">List[Global<wbr>Forwarding<wbr>Rule<wbr>Metadata<wbr>Filter<wbr>Filter<wbr>Label]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>filter<wbr>Match<wbr>Criteria</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Global<wbr>Forwarding<wbr>Rule<wbr>Metadata<wbr>Filter<wbr>Filter<wbr>Label</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/gcp/types/input/#GlobalForwardingRuleMetadataFilterFilterLabel">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/gcp/types/output/#GlobalForwardingRuleMetadataFilterFilterLabel">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-gcp/sdk/go/gcp/compute?tab=doc#GlobalForwardingRuleMetadataFilterFilterLabelArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-gcp/sdk/go/gcp/compute?tab=doc#GlobalForwardingRuleMetadataFilterFilterLabelOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Value</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Value</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>value</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>value</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

</dl>
{{% /choosable %}}









<h3>Package Details</h3>
<dl class="package-details">
	<dt>Repository</dt>
	<dd><a href="https://github.com/pulumi/pulumi-gcp">https://github.com/pulumi/pulumi-gcp</a></dd>
	<dt>License</dt>
	<dd>Apache-2.0</dd>
    
</dl>
