{
  "info": {
    "name": "Convert API Word to Image",
    "_postman_id": "06d82d73-8023-4fed-9a34-27eda8c2bee0",
    "description": "The API for converting Word documents to PDF files and Images. These file formats doc, docx, dot, dotx, wpd, wps, wri can be converted to png, jpg, tif.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Email",
      "item": [
        {
          "id": "027821cf-f15f-4a3c-9f1b-7f4525d9457f",
          "name": "email2image",
          "request": {
            "url": "http://do.convertapi.com/Email2Image?ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting E-Mail files to PDF files and Images. These file formats eml, mbx, msg, oft can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6731ef20-6be8-44be-8917-2b192b7428f3"
            }
          ]
        },
        {
          "id": "a85173e9-31f7-4834-b900-176840a2b971",
          "name": "email2pdf",
          "request": {
            "url": "http://do.convertapi.com/Email2Pdf?ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting E-Mail files to PDF files and Images. These file formats eml, mbx, msg, oft can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ce43cec3-3495-4a32-921f-a64c1af425d6"
            }
          ]
        }
      ]
    },
    {
      "name": "Excel",
      "item": [
        {
          "id": "7c3b0d72-d75f-4ae2-a55c-bdcaab88e651",
          "name": "excel2image",
          "request": {
            "url": "http://do.convertapi.com/Excel2Image?AlternativeParser=%7B%7D&ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D&WorksheetActive=%7B%7D&WorksheetIndex=%7B%7D&WorksheetName=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Excel documents to PDF files and Images. These file formats csv, xls, xlsb, xlsx, xlt, xltx can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1cf06333-99fd-4ff3-93da-205d32dd7c69"
            }
          ]
        },
        {
          "id": "d6332185-b7e3-439b-875c-aacffeee582f",
          "name": "excel2pdf",
          "request": {
            "url": "http://do.convertapi.com/Excel2Pdf?AlternativeParser=%7B%7D&ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D&WorksheetActive=%7B%7D&WorksheetIndex=%7B%7D&WorksheetName=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Excel documents to PDF files and Images. These file formats csv, xls, xlsb, xlsx, xlt, xltx can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "387d9e94-2083-448b-b3e3-81b11a35906a"
            }
          ]
        }
      ]
    },
    {
      "name": "Image",
      "item": [
        {
          "id": "a48900ee-a9ab-45f1-9676-51075b2be726",
          "name": "image2image",
          "request": {
            "url": "http://do.convertapi.com/Image2Image?ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Image files to PDF files and Images. These file formats avs, bmp, dcx, dib, dpx, fax, fits, fpx, gif, ico, iptc, jbig, jp2, jpeg, jpg, mdi, miff, mng, mpc, mtv, otb, pbm, pcd, pcds, pct, pcx, pgm, pict, png, pnm, ppm, psd, p7, ras, rgba, sun, tga, tiff, tif, vicar, vid, viff, wmf, xbm, xpm, xwd can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eba28bd0-a711-4389-a314-a6a1c3835bbc"
            }
          ]
        },
        {
          "id": "b43396b5-2c8a-4fa2-87e1-42c7e8d72a0b",
          "name": "image2pdf",
          "request": {
            "url": "http://do.convertapi.com/Image2Pdf?ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&Ocr=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Image files to PDF files and Images. These file formats avs, bmp, dcx, dib, dpx, fax, fits, fpx, gif, ico, iptc, jbig, jp2, jpeg, jpg, mdi, miff, mng, mpc, mtv, otb, pbm, pcd, pcds, pct, pcx, pgm, pict, png, pnm, ppm, psd, p7, ras, rgba, sun, tga, tiff, tif, vicar, vid, viff, wmf, xbm, xpm, xwd can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "03cfc836-b80e-4c98-878c-143a586c3d18"
            }
          ]
        }
      ]
    },
    {
      "name": "Journal",
      "item": [
        {
          "id": "52f7953c-77fc-4585-a839-7c0539799464",
          "name": "journal2image",
          "request": {
            "url": "http://do.convertapi.com/Journal2Image?ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Windows Journal Viewer documents to PDF files and Images. These file formats jnt can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f8817e2d-b46a-4b7c-9fef-78565166dce6"
            }
          ]
        },
        {
          "id": "9cbe7a82-c662-462a-80f6-bb2891011b52",
          "name": "journal2pdf",
          "request": {
            "url": "http://do.convertapi.com/Journal2Pdf?ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Windows Journal Viewer documents to PDF files and Images. These file formats jnt can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e16f150d-ac2a-4d80-a608-54138b2e42b2"
            }
          ]
        }
      ]
    },
    {
      "name": "Lotus",
      "item": [
        {
          "id": "6a728500-658e-4199-a9f2-e42e206b6984",
          "name": "lotus2image",
          "request": {
            "url": "http://do.convertapi.com/Lotus2Image?ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Lotus Smart Suite documents to PDF files and Images. These file formats 123, 12m, wk1, wk2, wk3, lwp, mwp, sam can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e3a46651-7328-47ee-aa3f-bc01dc9bd926"
            }
          ]
        },
        {
          "id": "f6ddfff1-8136-44c8-a52e-a9a72d34770a",
          "name": "lotus2pdf",
          "request": {
            "url": "http://do.convertapi.com/Lotus2Pdf?ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Lotus Smart Suite documents to PDF files and Images. These file formats 123, 12m, wk1, wk2, wk3, lwp, mwp, sam can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "18ca7cf1-27c7-4acd-9cab-cdd10c7bb7b0"
            }
          ]
        }
      ]
    },
    {
      "name": "Open",
      "item": [
        {
          "id": "769e2727-d04c-4b55-a4e3-2e24fef7abc7",
          "name": "openoffice2image",
          "request": {
            "url": "http://do.convertapi.com/OpenOffice2Image?AlternativeParser=%7B%7D&ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting OpenOffice documents to PDF files and Images. These file formats mml, odc, odf, odg, odi, odm, odp, ods, odt, otg, oth, otp, ots, pxl, sgl, smf, srw, stc, sti, stw, sxc, sxg, sxi, sxm, sxw, vor, wv2 can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f92d0f8a-381d-4c69-b782-ef36fb6e5fa3"
            }
          ]
        },
        {
          "id": "afe59c3d-70ad-43e4-9d11-61a3d271c956",
          "name": "openoffice2pdf",
          "request": {
            "url": "http://do.convertapi.com/OpenOffice2Pdf?AlternativeParser=%7B%7D&ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting OpenOffice documents to PDF files and Images. These file formats mml, odc, odf, odg, odi, odm, odp, ods, odt, otg, oth, otp, ots, pxl, sgl, smf, srw, stc, sti, stw, sxc, sxg, sxi, sxm, sxw, vor, wv2 can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f836244e-cb10-4309-9380-e034024ddeb9"
            }
          ]
        }
      ]
    },
    {
      "name": "PDF",
      "item": [
        {
          "id": "2ada74d8-36fb-42df-8b8e-1a62209830af",
          "name": "pdf2image",
          "request": {
            "url": "http://do.convertapi.com/Pdf2Image?ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting PDF documents to Image. These file formats pdf can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fcdf5112-dad4-4762-9064-55b90ec029aa"
            }
          ]
        },
        {
          "id": "c08646e4-561b-44eb-bc33-bf7218f005ed",
          "name": "pdf2pdf",
          "request": {
            "url": "http://do.convertapi.com/Pdf2Pdf?ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting PDF documents to Image. These file formats pdf can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "82be4586-5c6b-4936-8a44-531a8ee6baab"
            }
          ]
        },
        {
          "id": "5fce51e2-c319-4a38-9f9e-8cd1927f0dc0",
          "name": "pdf2powerpoint",
          "request": {
            "url": "http://do.convertapi.com/Pdf2PowerPoint?ApiKey=%7B%7D&File=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting PDF documents to PowerPoint presentation files. These file formats pdf, pdfa can be converted to pptx."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e71388e8-dc3a-44e7-831b-757b41cbb2c9"
            }
          ]
        }
      ]
    },
    {
      "name": "Script",
      "item": [
        {
          "id": "a3aa0655-160a-42d8-8011-695e545d506e",
          "name": "postscript2image",
          "request": {
            "url": "http://do.convertapi.com/PostScript2Image?ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting PostScript files to PDF files and Images. These file formats ps, eps, prn can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4102bc08-fbb3-4073-a3b5-3c8c7517fcc6"
            }
          ]
        },
        {
          "id": "15e82e4f-3211-4c6d-b04b-e6da117c563d",
          "name": "postscript2pdf",
          "request": {
            "url": "http://do.convertapi.com/PostScript2Pdf?ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting PostScript files to PDF files and Images. These file formats ps, eps, prn can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7bcaeb93-7b88-47c8-ab90-08b9a8036319"
            }
          ]
        }
      ]
    },
    {
      "name": "Power",
      "item": [
        {
          "id": "f6019a8e-77d4-4557-a8a2-5450ba4201cd",
          "name": "powerpoint2image",
          "request": {
            "url": "http://do.convertapi.com/PowerPoint2Image?AlternativeParser=%7B%7D&ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting PowerPoint documents to PDF files and Images. These file formats pot, potx, pps, ppsx, ppt, pptx can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "24321968-14fc-4cb1-b94f-1aabd5b80cec"
            }
          ]
        },
        {
          "id": "c6bd3c37-fa7b-485f-809e-f06d970bdb57",
          "name": "powerpoint2pdf",
          "request": {
            "url": "http://do.convertapi.com/PowerPoint2Pdf?AlternativeParser=%7B%7D&ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting PowerPoint documents to PDF files and Images. These file formats pot, potx, pps, ppsx, ppt, pptx can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e8d7926c-1385-476b-8d8e-7b5f140da4fd"
            }
          ]
        }
      ]
    },
    {
      "name": "Project",
      "item": [
        {
          "id": "80a25e8b-e3dd-44c1-a28e-5c740bea5fb2",
          "name": "project2image",
          "request": {
            "url": "http://do.convertapi.com/Project2Image?ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Project documents to PDF files and Images. These file formats mpp, mpt can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e7d64552-77c7-46ea-8f04-94b65214c6d4"
            }
          ]
        },
        {
          "id": "250b37e8-a3b0-474a-8ded-e8f893986467",
          "name": "project2pdf",
          "request": {
            "url": "http://do.convertapi.com/Project2Pdf?ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Project documents to PDF files and Images. These file formats mpp, mpt can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "07a23349-216d-4b94-8f8e-47674e7d8b32"
            }
          ]
        }
      ]
    },
    {
      "name": "Publisher",
      "item": [
        {
          "id": "c39143c0-983c-4790-85b0-8e6dd3dbe8c1",
          "name": "publisher2image",
          "request": {
            "url": "http://do.convertapi.com/Publisher2Image?AlternativeParser=%7B%7D&ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Publisher documents to PDF files and Images. These file formats pub can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aeb34036-ea7b-4724-9a13-4890ab1b1937"
            }
          ]
        },
        {
          "id": "389d5d22-3893-41a2-9515-8027a8d43d44",
          "name": "publisher2pdf",
          "request": {
            "url": "http://do.convertapi.com/Publisher2Pdf?AlternativeParser=%7B%7D&ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Publisher documents to PDF files and Images. These file formats pub can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e4d118a3-85b5-40bc-ab3d-f45441c651d0"
            }
          ]
        }
      ]
    },
    {
      "name": "Rich",
      "item": [
        {
          "id": "de8672ae-875e-4a2c-8a42-1cd2fd763c12",
          "name": "richtext2image",
          "request": {
            "url": "http://do.convertapi.com/RichText2Image?ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Rich Text documents to PDF files and Images. These file formats rtf can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d9f3904b-c19e-43cb-a06d-ddcddadddc4c"
            }
          ]
        },
        {
          "id": "dd40ef6f-2878-4da7-973c-2da851e65040",
          "name": "richtext2pdf",
          "request": {
            "url": "http://do.convertapi.com/RichText2Pdf?ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Rich Text documents to PDF files and Images. These file formats rtf can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "13bc12f9-05d6-4006-9bbf-c8141c758984"
            }
          ]
        }
      ]
    },
    {
      "name": "Snap",
      "item": [
        {
          "id": "370779e9-62b6-4d0b-82a6-9b23036548f2",
          "name": "snapshot2image",
          "request": {
            "url": "http://do.convertapi.com/SnapShot2Image?ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Access Report Snapshots documents to PDF files and Images. These file formats snp can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "234cb115-2f37-4597-ac02-61dda52f1490"
            }
          ]
        },
        {
          "id": "4f9738cc-144b-413b-8374-63593fc07b0a",
          "name": "snapshot2pdf",
          "request": {
            "url": "http://do.convertapi.com/SnapShot2Pdf?ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Access Report Snapshots documents to PDF files and Images. These file formats snp can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4e37c28a-e15e-4fd0-be3c-82387e00528b"
            }
          ]
        }
      ]
    },
    {
      "name": "Text",
      "item": [
        {
          "id": "7f8bf802-abdb-49fc-bc6e-9874080dc38b",
          "name": "text2image",
          "request": {
            "url": "http://do.convertapi.com/Text2Image?ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Textual files to PDF files and Images. These file formats txt, log can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c3905417-61b0-4c93-892d-efb30a0a5072"
            }
          ]
        },
        {
          "id": "622bf7a8-4188-4d17-a032-84fb80fbc187",
          "name": "text2pdf",
          "request": {
            "url": "http://do.convertapi.com/Text2Pdf?ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Textual files to PDF files and Images. These file formats txt, log can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6df278c8-3a1e-410f-9a19-0574bbd0077f"
            }
          ]
        }
      ]
    },
    {
      "name": "Visio",
      "item": [
        {
          "id": "31794d9a-0bf3-49f7-bdd9-1a4575df4a65",
          "name": "visio2image",
          "request": {
            "url": "http://do.convertapi.com/Visio2Image?AlternativeParser=%7B%7D&ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Visio documents to PDF files and Images. These file formats vsd, vst, vsdx, vstx can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e40c0437-90d7-4709-bce3-538c40cfa46d"
            }
          ]
        },
        {
          "id": "ee698fc7-1155-4803-986a-8fc72a954a1d",
          "name": "visio2pdf",
          "request": {
            "url": "http://do.convertapi.com/Visio2Pdf?AlternativeParser=%7B%7D&ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Visio documents to PDF files and Images. These file formats vsd, vst, vsdx, vstx can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "355d84e3-f94a-4b35-9800-8b8479eed58c"
            }
          ]
        }
      ]
    },
    {
      "name": "Web",
      "item": [
        {
          "id": "c65e2294-8bea-4188-a452-45196a7f4a13",
          "name": "web2image",
          "request": {
            "url": "http://do.convertapi.com/Web2Image?AcceptLanguage=%7B%7D&AlternativeParser=%7B%7D&ApiKey=%7B%7D&AuthPassword=%7B%7D&AuthUsername=%7B%7D&ConversionDelay=%7B%7D&CUrl=%7B%7D&PageHeight=%7B%7D&PageWidth=%7B%7D&Plugins=%7B%7D&Scripts=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D&UserAgent=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Web Pages to Images."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f87edd81-9285-4346-bdca-bfee75ede7bf"
            }
          ]
        },
        {
          "id": "8782b5bd-c3d7-4fbe-8c49-7c48cde2a3af",
          "name": "web2pdf",
          "request": {
            "url": "http://do.convertapi.com/Web2Pdf?AcceptLanguage=%7B%7D&AlternativeParser=%7B%7D&ApiKey=%7B%7D&AuthPassword=%7B%7D&AuthUsername=%7B%7D&Background=%7B%7D&ConversionDelay=%7B%7D&CoverUrl=%7B%7D&CUrl=%7B%7D&DocumentTitle=%7B%7D&FooterLine=%7B%7D&FooterSpacing=%7B%7D&FooterTextCenter=%7B%7D&FooterTextFont=%7B%7D&FooterTextLeft=%7B%7D&FooterTextRight=%7B%7D&FooterTextSize=%7B%7D&FooterUrl=%7B%7D&HeaderLine=%7B%7D&HeaderSpacing=%7B%7D&HeaderTextCenter=%7B%7D&HeaderTextFont=%7B%7D&HeaderTextLeft=%7B%7D&HeaderTextRight=%7B%7D&HeaderTextSize=%7B%7D&HeaderUrl=%7B%7D&InfoStamp=%7B%7D&LowQuality=%7B%7D&MarginBottom=%7B%7D&MarginLeft=%7B%7D&MarginRight=%7B%7D&MarginTop=%7B%7D&Outline=%7B%7D&PageHeight=%7B%7D&PageNo=%7B%7D&PageOrientation=%7B%7D&PageSize=%7B%7D&PageWidth=%7B%7D&Plugins=%7B%7D&PrintType=%7B%7D&Scripts=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D&UserAgent=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Web Pages to PDF files."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "71d84d69-d8a3-431b-b3a2-faa31ca9ea87"
            }
          ]
        }
      ]
    },
    {
      "name": "Word",
      "item": [
        {
          "id": "4e1ab490-0a29-4c74-aed3-9cf6f0b1f608",
          "name": "word2image",
          "request": {
            "url": "http://do.convertapi.com/Word2Image?AlternativeParser=%7B%7D&ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Word documents to PDF files and Images. These file formats doc, docx, dot, dotx, wpd, wps, wri can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2d53d744-7c16-4dab-a218-8c5d3410a520"
            }
          ]
        }
      ]
    }
  ]
}