---
title: ExportTemplate
description: API reference for ExportTemplate in Umbraco Commerce
---
## ExportTemplate

```csharp
public class ExportTemplate : ExportTemplateReadOnly
```

**Inheritance**

* class [ExportTemplateReadOnly](exporttemplatereadonly.md)

**Namespace**
* [Umbraco.Commerce.Core.Models](README.md)

### Methods

#### Create (1 of 2)

```csharp
public static ExportTemplate Create(IUnitOfWork uow, Guid storeId, string alias, string name)
```

---

#### Create (2 of 2)

```csharp
public static ExportTemplate Create(IUnitOfWork uow, Guid id, Guid storeId, string alias, 
    string name)
```


---

#### SetAlias

```csharp
public ExportTemplate SetAlias(string alias)
```


---

#### SetCategory

```csharp
public ExportTemplate SetCategory(TemplateCategory category)
```


---

#### SetExportStrategy

```csharp
public ExportTemplate SetExportStrategy(ExportStrategy exportStrategy)
```


---

#### SetFileExtension

```csharp
public ExportTemplate SetFileExtension(string fileExtension)
```


---

#### SetFileMimeType

```csharp
public ExportTemplate SetFileMimeType(string fileMimeType)
```


---

#### SetName (1 of 2)

```csharp
public ExportTemplate SetName(string name)
```

---

#### SetName (2 of 2)

```csharp
public ExportTemplate SetName(string name, string alias)
```


---

#### SetSortOrder

```csharp
public ExportTemplate SetSortOrder(int sortOrder)
```


---

#### SetTemplateView

```csharp
public ExportTemplate SetTemplateView(string templateViewPath)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->