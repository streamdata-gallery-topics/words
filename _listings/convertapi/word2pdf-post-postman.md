{
  "info": {
    "name": "Convert API Word to PDF",
    "_postman_id": "4c4f1c8c-d7f2-427d-84ed-843cd39755a3",
    "description": "The API for converting Word documents to PDF files and Images. These file formats doc, docx, dot, dotx, wpd, wps, wri can be converted to pdf, pdfa, png, jpg, tif.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Email",
      "item": [
        {
          "id": "f194b82a-6a36-4b60-adfc-239378df2754",
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
              "id": "7003efe7-2ed5-4299-ba6d-6254d63d4c23"
            }
          ]
        },
        {
          "id": "360c0150-b0e8-4a96-987e-cd71e52cdb83",
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
              "id": "74816f97-c4f5-4421-ba02-8d85a0c7cad2"
            }
          ]
        }
      ]
    },
    {
      "name": "Excel",
      "item": [
        {
          "id": "4ab15931-c231-4151-a98e-17028a8c8217",
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
              "id": "9ae93959-e71a-4d53-9013-c97a6d651ba1"
            }
          ]
        },
        {
          "id": "a9df79dd-0e65-484a-9e4e-5c55e1c7ced9",
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
              "id": "dcc3d08d-e70b-45c8-86b5-c624855c9b30"
            }
          ]
        }
      ]
    },
    {
      "name": "Image",
      "item": [
        {
          "id": "7cbeb21d-8752-42b8-a9ca-7956da7af4c0",
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
              "id": "98bf43a5-3da3-4a08-adad-22e9d8bfabbf"
            }
          ]
        },
        {
          "id": "8f449fa9-dabc-4a21-b02f-5dc8d047c195",
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
              "id": "e80b53cc-c2df-4844-9836-4fa65300cc2c"
            }
          ]
        }
      ]
    },
    {
      "name": "Journal",
      "item": [
        {
          "id": "0e9739c1-ff3a-45f9-b13a-5853908a47b9",
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
              "id": "cb8616a2-6619-4457-996c-1ebc70434aeb"
            }
          ]
        },
        {
          "id": "84586fb0-ab9a-4b0a-9f9d-f49b597e3c09",
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
              "id": "fdc5fab0-57b0-4c3b-8d0e-38ff49840c26"
            }
          ]
        }
      ]
    },
    {
      "name": "Lotus",
      "item": [
        {
          "id": "53bd355d-8b4e-4db7-ab47-8a41695e7963",
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
              "id": "eb1f77b3-c5a8-459f-9c8f-28a3956b1347"
            }
          ]
        },
        {
          "id": "d0c69295-b73b-4812-8ecc-fd6066a90eb3",
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
              "id": "efd92f62-c710-4e14-9839-72721ecd68db"
            }
          ]
        }
      ]
    },
    {
      "name": "Open",
      "item": [
        {
          "id": "235d9dd1-df21-449a-b76e-10efa6bf1b5f",
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
              "id": "76077612-a2e4-4da7-852d-d20d5d412c67"
            }
          ]
        },
        {
          "id": "8eaf4037-39f8-4d0e-9d1a-683531d0e4c4",
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
              "id": "f2c41314-8e40-4071-aadd-3179125a3b74"
            }
          ]
        }
      ]
    },
    {
      "name": "PDF",
      "item": [
        {
          "id": "e28d2346-f783-4c1d-9651-79ca910d55f8",
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
              "id": "e834910c-e9f9-49e7-badf-6890c378fdf8"
            }
          ]
        },
        {
          "id": "12a43c27-0129-47d9-abc3-67636b21315e",
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
              "id": "e2d49859-262c-497a-bde1-7a9862154014"
            }
          ]
        },
        {
          "id": "093fd0e0-faab-4795-843a-d6568099bb4b",
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
              "id": "901a04bd-e4d2-46ba-8495-a9eb8ce33058"
            }
          ]
        }
      ]
    },
    {
      "name": "Script",
      "item": [
        {
          "id": "36348e34-c2ba-48b5-a405-ad932af92b1d",
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
              "id": "2f7be46d-3c19-44e6-ad6a-9302fffbbfce"
            }
          ]
        },
        {
          "id": "c1de6697-41b9-4d3f-a0da-443d62aaac97",
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
              "id": "55f4d995-b956-4d61-9ac2-625dd1ba9cba"
            }
          ]
        }
      ]
    },
    {
      "name": "Power",
      "item": [
        {
          "id": "c9a62666-7d41-407d-8912-eac0c6692ff8",
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
              "id": "74f4b26d-7a99-4b9b-8e57-543431f78fbd"
            }
          ]
        },
        {
          "id": "1772e3df-0cd9-4c8e-a549-0f3860ce98b3",
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
              "id": "c7f8593c-3acf-4a0f-bd7f-c0e7acfdf9d3"
            }
          ]
        }
      ]
    },
    {
      "name": "Project",
      "item": [
        {
          "id": "7d8e4642-bb87-46b0-ae56-8f4c41dbb9ec",
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
              "id": "d57c535a-7b79-4683-8db0-176141145692"
            }
          ]
        },
        {
          "id": "be832ffd-78dc-45a8-9520-436398c01510",
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
              "id": "d1f5ec4c-d576-430e-82c9-ddbb489c2bb7"
            }
          ]
        }
      ]
    },
    {
      "name": "Publisher",
      "item": [
        {
          "id": "a1cd17df-c0a7-44a7-a180-d2fbc0136606",
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
              "id": "d507048a-c87f-42eb-b1c2-9298d15d89ed"
            }
          ]
        },
        {
          "id": "9e9fca36-a24a-4329-905b-2096f55c06ce",
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
              "id": "2738f7bb-5d9b-4dd5-813c-1eb326bf6209"
            }
          ]
        }
      ]
    },
    {
      "name": "Rich",
      "item": [
        {
          "id": "d1edd265-5ac4-4979-bbf0-8d8cb0460d53",
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
              "id": "ad81ac40-770d-47ca-80a7-79a323302667"
            }
          ]
        },
        {
          "id": "05729778-ebaa-4bfc-9ec7-174cb16253bd",
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
              "id": "cd7da4f5-1beb-4324-b07b-22659f69ce2b"
            }
          ]
        }
      ]
    },
    {
      "name": "Snap",
      "item": [
        {
          "id": "fa38976c-0a3c-4874-9412-f4bec94557ee",
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
              "id": "c45703fe-54da-425a-842f-379b41b6e854"
            }
          ]
        },
        {
          "id": "f4ba11eb-4e0f-4f15-9939-f162065ee778",
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
              "id": "c7e10948-b7df-44e3-b963-9fdb060403e6"
            }
          ]
        }
      ]
    },
    {
      "name": "Text",
      "item": [
        {
          "id": "61c7c172-e7f1-44ee-8545-18b91a76ff96",
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
              "id": "4d475bdf-245a-4335-be4f-53e9cbc5da88"
            }
          ]
        },
        {
          "id": "549d72dd-bfcb-4fe8-956a-0fa1c1cdced8",
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
              "id": "dd2975b1-7b9a-4505-82ce-d94ed071c78d"
            }
          ]
        }
      ]
    },
    {
      "name": "Visio",
      "item": [
        {
          "id": "b015aba3-7b5d-4580-9c61-3bf4883aa6f8",
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
              "id": "0b90cf5d-752a-47a7-b885-03d46781e91b"
            }
          ]
        },
        {
          "id": "da134566-9aa5-4fc5-990c-ae7a9efd65a3",
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
              "id": "1c78e13f-d897-4952-9917-ed85689a18d3"
            }
          ]
        }
      ]
    },
    {
      "name": "Web",
      "item": [
        {
          "id": "0e937281-8425-432c-abc7-7770dbfafdcf",
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
              "id": "dc26f368-349d-4fd5-adcc-dd4f2a78550a"
            }
          ]
        },
        {
          "id": "8e865ac1-0000-4dfe-a41f-d076927e089a",
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
              "id": "162dbb56-78aa-4f16-8ea7-1d2eb714bc59"
            }
          ]
        }
      ]
    },
    {
      "name": "Word",
      "item": [
        {
          "id": "10cb59b0-4e77-495d-b7dd-ed3179f1b1fa",
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
              "id": "9873cd8f-3a2f-491d-813c-f44c2668570d"
            }
          ]
        },
        {
          "id": "ea283c43-4ca9-4f57-a384-10b99ba78f1c",
          "name": "word2pdf",
          "request": {
            "url": "http://do.convertapi.com/Word2Pdf?AlternativeParser=%7B%7D&ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Word documents to PDF files and Images. These file formats doc, docx, dot, dotx, wpd, wps, wri can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c4f77ce3-8b4a-4e8e-b3f7-8b1fb3c01369"
            }
          ]
        }
      ]
    }
  ]
}