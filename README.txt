Data for BIANCA

--
-- TOC entry 2070 (class 0 OID 18784)
-- Dependencies: 177
-- Data for Name: clones; Type: TABLE DATA; Schema: public; Owner: math
--
-- time_origin (timestamp)
-- commit_origin (SHA1)
-- time_dest (timestamp)
-- commit_dest (SHA1)S

--
--
-- TOC entry 2075 (class 0 OID 16410)
-- Dependencies: 174
-- Data for Name: commits; Type: TABLE DATA; Schema: public; Owner: math
-- 
-- repository_id (fk repo), 
-- commit_hash, 
-- author_name, 
-- author_date_unix_timestamp, 
-- author_email, 
-- author_date, 
-- commit_message, 
-- fix (boolean), 
-- classification (corrective, preventive, ...), 
-- linked (to an issue), 
-- contains_bug (boolean), 
-- fixes (SHA1 of fixing commits),
-- For the rest, see Rosen, Christoffer, Ben Grawi, and Emad Shihab. "Commit guru: Analytics and risk prediction of software commits." Proceedings of the 2015 10th Joint Meeting on Foundations of Software Engineering. ACM, 2015.
-- ns, 
-- nd, 
-- nf, 
-- entrophy, 
-- la, 
-- ld, 
-- fileschanged, 
-- lt, 
-- ndev, 
-- age, 
-- nuc, 
-- exp, 
-- rexp, 
-- sexp, 
-- glm_probability


--
-- TOC entry 2074 (class 0 OID 16402)
-- Dependencies: 173
-- Data for Name: repositories; Type: TABLE DATA; Schema: public; Owner: math
-- 
-- id (UUID)
-- name (Name of the repo)
-- url (Github URL)
-- creation_date
-- ingestion_date (Data first analyzed)
-- last_ingested_commit (Last SHA1 analyzed)
-- analysis_date (Data Last analyzed), 
-- status (Not used), 
-- email (Not used), 
-- listed (Not used), 
-- last_data_dump (Not used)