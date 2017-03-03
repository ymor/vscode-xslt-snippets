# XSLT Snippets for Visual Studio Code

Handful snippets for working with xslt templates.

## Snippets

| Prefix      | Description                                                                                    |
| ----------- | ---------------------------------------------------------------------------------------------- |
| cm        | `<!-- $1 -->`                                                                                  |
| var       | `<xsl:variable name="$1">$2</xsl:variable>`                                                    |
| val       | `<xsl:value-of select="$1" />`                                                                 |
| choose    | `<xsl:choose><xsl:when test="$1">$2</xsl:when><xsl:otherwise>$3</xsl:otherwise</xsl:choose>`   |
| when      | `<xsl:when test="$1">$2</xsl:when>`                                                            |
| otherwise | `<xsl:otherwise>$1</xsl:otherwise>`                                                            |
| if        | `<xsl:if test="$1">$2</xsl:if>`                                                                |
| temp      | `<xsl:template match="$1">$2</xsl:template>`                                                   |
| param     | `<xsl:param name="$1" />`                                                                      |
| with      | `<xsl:with-param name="$1" select="$2" />`                                                     |
| attribute | `<xsl:attribute name="$1">$2</xsl:attribute>`                                                  |
| text      | `<xsl:text>$1</xsl:text>`                                                                      |
| apply     | `<xsl:apply-templates match="$1" />`                                                           |      
